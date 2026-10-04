---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20131404?"
user: cmoussa1
date: 2026-10-02
repo_name: flux-framework/flux-accounting
html_url: https://github.com/flux-framework/flux-accounting/issues/980
repo_url: https://github.com/flux-framework/flux-accounting
---

<a href='https://github.com/cmoussa1' target='_blank'>cmoussa1</a> commented on issue <a href='https://github.com/flux-framework/flux-accounting/issues/980' target='_blank'>flux-framework/flux-accounting#980</a>.

<small>To consider a design that might fit both `mf_priority.cpp` and `resource_quotas.cpp`'s separate use cases (while taking into consideration they are trying to accomplish the same thing), we could design the `Usage` type to be as primitive as possible, i.e. isolate it from users, queues, associations, dependencies, Flux callbacks, or where the limits come from. It should basically only know how to represent and do arithmetic on 