---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2072964?"
user: BradWhitlock
date: 2026-10-24
repo_name: llnl/axom
html_url: https://github.com/llnl/axom/issues/2022
repo_url: https://github.com/llnl/axom
---

<a href='https://github.com/BradWhitlock' target='_blank'>BradWhitlock</a> commented on issue <a href='https://github.com/llnl/axom/issues/2022' target='_blank'>llnl/axom#2022</a>.

<small>I saw Umpire has some thread-safe allocators/pools. I think we're just not calling them in Axom so inside some of our `axom::for_all` loops where we make primal objects that end up allocating through Umpire, we get segfaults because the threads are not able to coordinate their allocations via Umpire. Suppose we added some extra bits inside `axom::for_all` and the `execution_space<OMP_EXEC>` specialization:...</small>

<a href='https://github.com/llnl/axom/issues/2022' target='_blank'>View Comment</a>