---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2024-09-13
repo_name: rsmpi/rsmpi
html_url: https://github.com/rsmpi/rsmpi/issues/197
repo_url: https://github.com/rsmpi/rsmpi
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/rsmpi/rsmpi/issues/197' target='_blank'>rsmpi/rsmpi#197</a>.

<small>I'd be curious to test if you have a reproducer with the same MPI implementation, but I don't think rsmpi has anything (directly) to do with this behavior. In general, there isn't a guarantee about orderly termination. It's possible that the errors in C are calling `MPI_Abort` while Rust errors are not....</small>

<a href='https://github.com/rsmpi/rsmpi/issues/197' target='_blank'>View Comment</a>