---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2022-09-12
repo_name: flux-framework/flux-accounting
html_url: https://github.com/flux-framework/flux-accounting/issues/262
repo_url: https://github.com/flux-framework/flux-accounting
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-accounting/issues/262' target='_blank'>flux-framework/flux-accounting#262</a>.

<small>Good catch Chris! Maybe for now you could look at the code where the bank entry is assigned and ensure the "DNE" entry is never used, logging an error when it is and skipping to the next non-DNE bank as the default. This would let us catch when this problem is occurring, while at the same time possibly fixing the issue....</small>

<a href='https://github.com/flux-framework/flux-accounting/issues/262' target='_blank'>View Comment</a>