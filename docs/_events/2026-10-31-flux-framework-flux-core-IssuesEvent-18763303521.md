---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2026-10-31
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/7884
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/7884' target='_blank'>flux-framework/flux-core#7884</a>.

<p>job-info: in-flight lookup requests are unanswered on module unload</p><small>Problem:  If `job-info` is unloaded while a `job-info.lookup` request is in flight, `lookup_cleanup()` destroys the pending lookup context without responding.  The requester blocks forever....</small><a href='https://github.com/flux-framework/flux-core/issues/7884' target='_blank'>View Comment</a>