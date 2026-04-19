---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2026-04-18
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/7546
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/7546' target='_blank'>flux-framework/flux-core#7546</a>.

<small>BTW, the IMP itself isn't aware of how the `imp-exec-helper` obtains the input to the IMP. For now we could fetch `DeviceAllow` and `DevicePolicy` from systemd (perhaps rewrite to some input more suitable for use with the IMP so we don't have to re-implement systemd DeviceAllow parsing), in the future if this data needs to come from outside systemd, an alternate method could replace or even be added to the helper....</small>

<a href='https://github.com/flux-framework/flux-core/pull/7546' target='_blank'>View Comment</a>