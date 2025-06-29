---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2025-06-26
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6887
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/6887' target='_blank'>flux-framework/flux-core#6887</a>.

<small>I was mistaken. `pthread_cancel()` is only called on each broker module during broker shutdown, from  [modhash_destroy()](https://github.com/flux-framework/flux-core/blob/master/src/broker/modhash.c#L639-L663)...</small>

<a href='https://github.com/flux-framework/flux-core/issues/6887' target='_blank'>View Comment</a>