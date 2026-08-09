---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2026-08-07
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1544
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1544' target='_blank'>flux-framework/flux-sched#1544</a>.

<small>Ok, clearly we have some digging to do here.  The sitting in sched forever issue would normally mean something like there being too many elements in `down` state to schedule the job, or otherwise held onto.  It would be good to get a snapshot of the state of the agfilters and rabbits if we can, I think `find` can do that.  Anything that could let us see if there's some inconsistent state would be good, because while the hung sched state could be things being down, the unsatisfiable result should only be if there flat isn't enough hardware accessible at this point....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1544' target='_blank'>View Comment</a>