---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2024-05-17
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/5987
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/5987' target='_blank'>flux-framework/flux-core#5987</a>.

<p>hostlist: perf issue in `hostlist_find_host()` due to `hostname_create()`</p><small>@trws noted in some perf benchmarking of Fluxion that `hostlist_find_host()` and specifically `hostname_create()` was taking a large percentage of time due mainly to the `calloc(3)` used in creating the `struct hostname` used for matching purposes....</small><a href='https://github.com/flux-framework/flux-core/issues/5987' target='_blank'>View Comment</a>