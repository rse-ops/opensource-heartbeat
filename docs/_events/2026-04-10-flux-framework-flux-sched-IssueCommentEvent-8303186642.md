---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2026-04-10
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1424
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/1424' target='_blank'>flux-framework/flux-sched#1424</a>.

<small>I'm digging into this now, and I'm pretty sure I have a handle on what's going on.  Fluxion sets the expected start time as an annotation, and sends that along to core.  Core interprets time of now or earlier as "now." Both of these are fine independently, but sched tries to avoid sending too many annotations because of some old issues with memory ballooning due to too many annotations....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/1424' target='_blank'>View Comment</a>