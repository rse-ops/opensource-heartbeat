---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20131404?"
user: cmoussa1
date: 2026-07-24
repo_name: flux-framework/flux-accounting
html_url: https://github.com/flux-framework/flux-accounting/pull/916
repo_url: https://github.com/flux-framework/flux-accounting
---

<a href='https://github.com/cmoussa1' target='_blank'>cmoussa1</a> commented on issue <a href='https://github.com/flux-framework/flux-accounting/pull/916' target='_blank'>flux-framework/flux-accounting#916</a>.

<small>Thanks for catching that issue in the commit message @jameshcorbett - I'll go ahead and remove that from the message altogether. The `.backup` DBs are automatically cleaned up in the testsuite, but you are right, the backup isn't deleted if the update completes successfully. I guess the thinking here was that it would be an admin's responsibility to manually clean this up for this reason:...</small>

<a href='https://github.com/flux-framework/flux-accounting/pull/916' target='_blank'>View Comment</a>