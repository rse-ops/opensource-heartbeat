---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-12-19
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1423
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1423' target='_blank'>flux-framework/flux-sched#1423</a>.

<small>Doing it in that literal order is impossible. We may be able to get you to something like what you want, but let me lay out the situation a bit so you know where I'm coming from.  In order to give a predicted start time we need to run a match against the current resource state, allocations and reservations to determine when the job would be reserved.  Without doing that match, any result we give out would be even more wrong than without doing it (even doing the match is still an estimate at best due to new job arrival and constant state changes)....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1423' target='_blank'>View Comment</a>