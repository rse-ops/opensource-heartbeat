---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-08-15
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1015
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1015' target='_blank'>flux-framework/flux-sched#1015</a>.

<small>I actually did some digging on this, so some more context. We only show an ETA for those jobs that enter the reserved state. Since we normally run easy backfill, that means only the highest priority job that can't run immediately gets an estimated time. If we run with conservative, then we should get estimates up to reservation depth (which is usually shorter than full backfill depth). ...</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1015' target='_blank'>View Comment</a>