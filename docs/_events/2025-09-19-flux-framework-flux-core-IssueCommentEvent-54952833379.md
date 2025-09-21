---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2025-09-19
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/7067
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/7067' target='_blank'>flux-framework/flux-core#7067</a>.

<small>I found it.  The `msg_deque` class uses an `eventfd(2)` internally which raises POLLOUT when a pending POLLIN event is cleared.  Fix coming....</small>

<a href='https://github.com/flux-framework/flux-core/issues/7067' target='_blank'>View Comment</a>