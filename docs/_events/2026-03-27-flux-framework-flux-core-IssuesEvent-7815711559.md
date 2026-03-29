---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2026-03-27
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/7494
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/7494' target='_blank'>flux-framework/flux-core#7494</a>.

<p>idset: `idset_set (idset, -586)` caused `SIGABRT`</p><small>As part of https://github.com/flux-framework/flux-sched/pull/1438 I tried passing some negative integers to `idset_set` and found that passing `-586` (which I picked randomly) caused my process to be killed with `SIGABRT`. I noticed the following assertion message in my test output:...</small><a href='https://github.com/flux-framework/flux-core/issues/7494' target='_blank'>View Comment</a>