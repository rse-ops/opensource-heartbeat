---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2026-03-27
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/pull/1432
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/pull/1432' target='_blank'>flux-framework/flux-sched#1432</a>.

<small>Aside from [229e25d](https://github.com/flux-framework/flux-sched/pull/1432/commits/229e25d56c126f8c473f72f0e9df0d4405fe677f), there are no code changes from @milroy 's last review. However, I did add some new tests in the last commit. The tests fail because the agfilter output is incorrect for cores: it considers fewer cores to be allocated than are in fact allocated. This discrepancy appears to have something to do with the match format and the way it skips vertices, because if the test is re-run with `rv1` match format instead of `rv1_shorthand`, or if the job is modified to only request nodes non-exclusively, the agfilter checks pass. ...</small>

<a href='https://github.com/flux-framework/flux-sched/pull/1432' target='_blank'>View Comment</a>