---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2025-08-18
repo_name: flux-framework/flux-coral2
html_url: https://github.com/flux-framework/flux-coral2/issues/390
repo_url: https://github.com/flux-framework/flux-coral2
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> open issue <a href='https://github.com/flux-framework/flux-coral2/issues/390' target='_blank'>flux-framework/flux-coral2#390</a>.

<p>dws: move more logic to separate threads</p><small>Profiling data on LC systems reveals that the `coral2_dws` script spends most of its time in kubernetes calls. As a step towards fixing #289, it might be a good idea to move more kubernetes logic to separate threads. The logic encapsulated by `flux_k8s.workflow.WorkflowInfo.move_to_teardown` could be moved to the `flux_k8s.cleanup` module and that module's coroutines. Also, `flux_k8s.storage.init_rabbits` could start watching `Storage` resources in a separate thread....</small><a href='https://github.com/flux-framework/flux-coral2/issues/390' target='_blank'>View Comment</a>