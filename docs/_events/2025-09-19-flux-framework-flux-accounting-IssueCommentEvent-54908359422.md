---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20131404?"
user: cmoussa1
date: 2025-09-19
repo_name: flux-framework/flux-accounting
html_url: https://github.com/flux-framework/flux-accounting/issues/749
repo_url: https://github.com/flux-framework/flux-accounting
---

<a href='https://github.com/cmoussa1' target='_blank'>cmoussa1</a> commented on issue <a href='https://github.com/flux-framework/flux-accounting/issues/749' target='_blank'>flux-framework/flux-accounting#749</a>.

<small>I was able to reproduce this pretty easily in a Docker container where an association has `max_nodes` and `max_cores` limits of 1 each and submits two 1-node jobs. The second one gets held due to `max-resources-user-limit`, but even after upping the association's limits and updating the plugin with `flux account-priority-update`, the second job remains in DEPEND state....</small>

<a href='https://github.com/flux-framework/flux-accounting/issues/749' target='_blank'>View Comment</a>