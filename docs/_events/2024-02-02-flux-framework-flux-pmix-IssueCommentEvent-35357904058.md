---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/13199119?"
user: wihobbs
date: 2024-02-02
repo_name: flux-framework/flux-pmix
html_url: https://github.com/flux-framework/flux-pmix/issues/31
repo_url: https://github.com/flux-framework/flux-pmix
---

<a href='https://github.com/wihobbs' target='_blank'>wihobbs</a> commented on issue <a href='https://github.com/flux-framework/flux-pmix/issues/31' target='_blank'>flux-framework/flux-pmix#31</a>.

<small>Bumping this, as testing on Dane suggests that pmix's calling into `hwloc` to load topology for each core causes `MPI_Init` to be painfully slow, especially on systems with a lot of cores (Dane has 112 per node). We can get around this for now by setting `HWLOC_XMLFILE`. Results with and without that variable set:...</small>

<a href='https://github.com/flux-framework/flux-pmix/issues/31' target='_blank'>View Comment</a>