---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-08-14
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4534
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/4534' target='_blank'>flux-framework/flux-core#4534</a>.

<small>Yeah, we do.  Asking hwloc would be ok, and actually if we have a topology or a way to refer to the gpu device there that would make the ID translation issue trivial to fix too because it's the same object we'd want to query.  The ultimate solution would be to pull the unique ID for each GPU from it, and then use that in whichever env var is for the GPU (to handle changing GPU orders and multiple runtimes on a machine) but for systems that _actually exist_ outside my office, all we really need is:...</small>

<a href='https://github.com/flux-framework/flux-core/issues/4534' target='_blank'>View Comment</a>