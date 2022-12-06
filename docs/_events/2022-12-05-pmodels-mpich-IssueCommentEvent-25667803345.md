---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-12-05
repo_name: pmodels/mpich
html_url: https://github.com/pmodels/mpich/issues/6319
repo_url: https://github.com/pmodels/mpich
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/pmodels/mpich/issues/6319' target='_blank'>pmodels/mpich#6319</a>.

<small>Thanks. The standard seems to allow it, but there is no reference counting on the parent. If we're calling `MPI_Finalize`, then I think it's okay. If a user initializes MPI (e.g., in their C code) and then calls Rust code that uses rsmpi to spawn, I don't love the idea of it then becoming the users responsibility to figure out when they need to free the parent communicator....</small>

<a href='https://github.com/pmodels/mpich/issues/6319' target='_blank'>View Comment</a>