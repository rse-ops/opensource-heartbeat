---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/15018133?"
user: gardner48
date: 2026-06-11
repo_name: llnl/sundials
html_url: https://github.com/llnl/sundials/issues/957
repo_url: https://github.com/llnl/sundials
---

<a href='https://github.com/gardner48' target='_blank'>gardner48</a> commented on issue <a href='https://github.com/llnl/sundials/issues/957' target='_blank'>llnl/sundials#957</a>.

<small>When using an implicit method with the default nonlinear solver (Newton's method) you need to create and attach a linear solver before evolving the problem in time. The lines starting [here](https://github.com/llnl/sundials/blob/0a1024b7fb902a5eae3142adf8c13561c6989543/examples/arkode/C_serial/ark_analytic.c#L117) in the `ark_analytic.c` example show how to do this for a dense linear solver (and matrix). There should be a runtime error in this case, but it seems there is a missing check....</small>

<a href='https://github.com/llnl/sundials/issues/957' target='_blank'>View Comment</a>