---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2025-10-24
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/7168
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/7168' target='_blank'>flux-framework/flux-core#7168</a>.

<small>Well, I don't actually see anything in RFC 44 that says an undrain event can only be posted for ranks that were previously drained, so one idea would be to add a new "mode" to the undrain RPC like "update" which simply posts an extra `undrain` event to the eventlog with the new `reason`. A tool would then have to process the entire resource eventlog to be sure the most updated undrain reason event for any given rank has been processed (instead of assuming the first `undrain` event after the corresponding `drain` event has the correct `reason`)....</small>

<a href='https://github.com/flux-framework/flux-core/issues/7168' target='_blank'>View Comment</a>