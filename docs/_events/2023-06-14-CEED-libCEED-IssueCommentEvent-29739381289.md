---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-06-14
repo_name: CEED/libCEED
html_url: https://github.com/CEED/libCEED/pull/1227
repo_url: https://github.com/CEED/libCEED
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/CEED/libCEED/pull/1227' target='_blank'>CEED/libCEED#1227</a>.

<small>@nbeams @jeremylt PETSc sets `HIPCCFLAGS` based on its configure and user-specified options, thus was losing the `-I` flags that were being put into that variable. Preprocessor defines are intended to go in `CPPFLAGS` partly for this reason so that's what this PR does. It also removes `-I/opt/rocm/include` from the command-line for files that don't need HIP headers....</small>

<a href='https://github.com/CEED/libCEED/pull/1227' target='_blank'>View Comment</a>