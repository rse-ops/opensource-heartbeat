---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2026-11-14
repo_name: flux-framework/flux-coral2
html_url: https://github.com/flux-framework/flux-coral2/issues/516
repo_url: https://github.com/flux-framework/flux-coral2
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> open issue <a href='https://github.com/flux-framework/flux-coral2/issues/516' target='_blank'>flux-framework/flux-coral2#516</a>.

<p>Multiple coral2-dws instances per K8s instance</p><small>During a meeting yesterday, some LC admins described their interest in converting CORAL2 clusters piecemeal to the RHEL10-based TOSS6 operating system. They want to have some part of the cluster be running TOSS4 and the rest running TOSS6. However they want a pretty strong separation between the partitions--certainly no jobs spanning the partition, for instance. One option is to set up a single Flux instance with queues that are either all T6 nodes or all T4 nodes, plus some additional restrictions. However, another option would be to have two different flux instances, one for T6 and one for T4. The trouble with that is that there is only one rabbit-k8s infrastructure for the whole cluster, so there would need to be support for two DWS plugins talking to the same rabbit k8s....</small><a href='https://github.com/flux-framework/flux-coral2/issues/516' target='_blank'>View Comment</a>