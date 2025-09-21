---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-09-18
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1383
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1383' target='_blank'>flux-framework/flux-sched#1383</a>.

<small>Yeah, I think what's happening is that the FCFS policy is treating the unsatisfiable job as the first job that couldn't match.  When that happens it stops trying to schedule more work, because more work can't fit, but because that job is actually being rejected completely that assumption is wrong.  The `set_schedulability (true)` is what we need to have happen....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1383' target='_blank'>View Comment</a>