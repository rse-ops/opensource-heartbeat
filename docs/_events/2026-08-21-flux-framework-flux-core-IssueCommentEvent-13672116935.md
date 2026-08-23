---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2026-08-21
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/7778
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/7778' target='_blank'>flux-framework/flux-core#7778</a>.

<small>Hit another case in the reproducer where `ECONNRESET` is returned from the read. This never caused the spin loop issue before (like `EBADF`), because apparently it is a oneshot error. The code before #7777 was merged just ignored the error and returned, so the next read got EOF and closed the stream....</small>

<a href='https://github.com/flux-framework/flux-core/issues/7778' target='_blank'>View Comment</a>