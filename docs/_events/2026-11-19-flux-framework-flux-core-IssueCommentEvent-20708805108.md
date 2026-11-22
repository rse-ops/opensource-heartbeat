---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2026-11-19
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/7858
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/7858' target='_blank'>flux-framework/flux-core#7858</a>.

<small>I've pushed a new version that addresses the review comments and given it some testing on my home cluster.  This version adds a little eventlog for each unit stored in the flux system instance's XDG_RUNTIME_DIR.  An ExecStopPost script appends the exit status when the unit finishes so the status is recorded even when Flux is offline.  For waitable procs the eventlog persists until the status is collected by a wait RPC so that it can survive any number of Flux restarts....</small>

<a href='https://github.com/flux-framework/flux-core/pull/7858' target='_blank'>View Comment</a>