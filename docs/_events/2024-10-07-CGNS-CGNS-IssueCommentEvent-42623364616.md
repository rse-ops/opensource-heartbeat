---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2024-10-07
repo_name: CGNS/CGNS
html_url: https://github.com/CGNS/CGNS/pull/778
repo_url: https://github.com/CGNS/CGNS
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/CGNS/CGNS/pull/778' target='_blank'>CGNS/CGNS#778</a>.

<small>FWIW, that is still a race condition in serial. It might not trigger frequently because people aren't super likely to have a concurrent job (possibly on a different machine that accesses the same network file system) moving/replacing files, but that does happen. Even if the file still exists between the probe and open call, it could have been replaced by one with a different file type (ADF vs HDF5). It's kind of unfortunate there is no H5F open with file descriptor to avoid such races....</small>

<a href='https://github.com/CGNS/CGNS/pull/778' target='_blank'>View Comment</a>