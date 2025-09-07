---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/15018133?"
user: gardner48
date: 2025-09-04
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/pull/728
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/gardner48' target='_blank'>gardner48</a> commented on issue <a href='https://github.com/LLNL/sundials/pull/728' target='_blank'>LLNL/sundials#728</a>.

<small>> @gardner48 Looks like the extended precision test for `cvsRoberts_FSA_dns_constraints_-sensi_stg1_t.c` is failing because a line number is in the output file (due to an error message, see [sundials-codes/answers#60](https://github.com/sundials-codes/answers/pull/60)) , and the line number changed. We should probably just disable that test with extended precision since it fails....</small>

<a href='https://github.com/LLNL/sundials/pull/728' target='_blank'>View Comment</a>