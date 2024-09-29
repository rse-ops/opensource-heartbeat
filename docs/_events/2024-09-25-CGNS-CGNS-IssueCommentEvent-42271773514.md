---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2024-09-25
repo_name: CGNS/CGNS
html_url: https://github.com/CGNS/CGNS/pull/778
repo_url: https://github.com/CGNS/CGNS
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/CGNS/CGNS/pull/778' target='_blank'>CGNS/CGNS#778</a>.

<small>`access` is always racy if the calling code has logic depending on the result. Suppose an archival job is running in the background, moving files to slower storage after a certain age. Then your production job checks `access` and sees the file, but it's gone by the time it tries to open it. It is likely that `access` will be formally deprecated in a future version of POSIX. I think CGNS is important enough that it should not rely on such race conditions, and instead correctly handle errors from the likes of `H5Fopen`....</small>

<a href='https://github.com/CGNS/CGNS/pull/778' target='_blank'>View Comment</a>