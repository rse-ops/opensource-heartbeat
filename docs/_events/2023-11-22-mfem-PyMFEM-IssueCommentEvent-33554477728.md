---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2023-11-22
repo_name: mfem/PyMFEM
html_url: https://github.com/mfem/PyMFEM/issues/200
repo_url: https://github.com/mfem/PyMFEM
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/PyMFEM/issues/200' target='_blank'>mfem/PyMFEM#200</a>.

<small>It looks like the issue is in the python wrapper -- in the C++ code the first argument to both `PrintVTK` and `SaveVTK` is an output stream which should be the same file -- both methods just append to the stream. In your code snippet, it looks like the python wrapper replaces the first argument with just a file name and internally re-opens the file in `SaveVTK` and that truncates it and overwrites the output from `PrintVTK`. Maybe there is a version of `SaveVTK` in the python version that uses a file handle (or something like that) that can be used in both `PrintVTK` and `SaveVTK` to prevent the overwriting? @sshiraiwa, is this possible in the python version?...</small>

<a href='https://github.com/mfem/PyMFEM/issues/200' target='_blank'>View Comment</a>