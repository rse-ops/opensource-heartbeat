---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2026-06-25
repo_name: llnl/RAJA
html_url: https://github.com/llnl/RAJA/pull/2006
repo_url: https://github.com/llnl/RAJA
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/llnl/RAJA/pull/2006' target='_blank'>llnl/RAJA#2006</a>.

<small>Honestly I think it does, at least in as much as when `iter + stride` is executed we want the result to be of the same type as `iter`.  I suppose it wouldn't _have_ to be, but if not it would have to be convertible to the type of iter and that seems a bit harder to reason about. Also even if we actually do re-order them based on the sign of the stride, in a logical sense I think of it more like:...</small>

<a href='https://github.com/llnl/RAJA/pull/2006' target='_blank'>View Comment</a>