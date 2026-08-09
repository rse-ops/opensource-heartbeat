---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/6393677?"
user: adayton1
date: 2026-08-07
repo_name: llnl/RAJA
html_url: https://github.com/llnl/RAJA/issues/448
repo_url: https://github.com/llnl/RAJA
---

<a href='https://github.com/adayton1' target='_blank'>adayton1</a> commented on issue <a href='https://github.com/llnl/RAJA/issues/448' target='_blank'>llnl/RAJA#448</a>.

<small>There's no critical section anymore. We now use `#pragma omp atomic capture compare` from OpenMP 5.1 if it is available, otherwise fall back to the built in case with the early exit. Closing and we will open a new issue if/when performance becomes an issue again....</small>

<a href='https://github.com/llnl/RAJA/issues/448' target='_blank'>View Comment</a>