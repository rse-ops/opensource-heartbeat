---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2025-09-19
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/7069
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/7069' target='_blank'>flux-framework/flux-core#7069</a>.

<small>Yeah, it is subtle. "requires" defines a dependency relationship, while "before" and "after" are strictly for ordering or precedence of active tasks. If task A requires task B, and task A is active, then task B is forced to be active as well. However, at this point A can run in parallel with B. If A needs to be loaded before or after B, then "before" or "after" should be used to determine the precedence of tasks....</small>

<a href='https://github.com/flux-framework/flux-core/pull/7069' target='_blank'>View Comment</a>