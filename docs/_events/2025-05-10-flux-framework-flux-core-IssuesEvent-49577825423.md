---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2025-05-10
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/6807
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/6807' target='_blank'>flux-framework/flux-core#6807</a>.

<p>broker: available TBON topology options are not great for resilient batch jobs</p><small>Problem: as noted in #6806, performance issues have been observed with large batch jobs run with  `-Stbon.topo=kary:0` (flat topology).  This is currently recommended when resiliency is required, to minimize the number of critical router nodes.  Unfortunately, there is no convenient way just add a few router nodes to an otherwise flat topology to alleviate the bottleneck on rank 0.  You have to go all in with kary or binomial....</small><a href='https://github.com/flux-framework/flux-core/issues/6807' target='_blank'>View Comment</a>