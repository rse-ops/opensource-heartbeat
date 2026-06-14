---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2026-06-11
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/7467
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/7467' target='_blank'>flux-framework/flux-core#7467</a>.

<small>It might actually be better to just add a FLUX_MSGGFLAG_COMPOUND flag to indicate that the payload is compound (steal FLUX_MSGFLAG_USER1), and rather than  requiring JSONL, use size prefixed segments.  Then a message could contain multiple raw payloads, which could potentially avoid base64 encoding in KVS commit messages, and allow batching of content load/store payloads....</small>

<a href='https://github.com/flux-framework/flux-core/issues/7467' target='_blank'>View Comment</a>