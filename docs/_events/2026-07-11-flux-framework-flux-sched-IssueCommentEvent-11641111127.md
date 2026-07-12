---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2026-07-11
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/pull/1528
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/pull/1528' target='_blank'>flux-framework/flux-sched#1528</a>.

<small>That's a fair point.  The advantage to having the reserved boolean tracked here is I think I would need to do the same thing to solve #1424, because we need to know that something was reserved (and thus sent a time estimate) to clear those estimates the next time around.  I suppose we could separate them and set "reserved" along with the time estimate but not track that it was reserved at the end? ...</small>

<a href='https://github.com/flux-framework/flux-sched/pull/1528' target='_blank'>View Comment</a>