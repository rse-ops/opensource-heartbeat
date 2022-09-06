---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2022-09-05
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4536
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> closed issue <a href='https://github.com/flux-framework/flux-core/issues/4536' target='_blank'>flux-framework/flux-core#4536</a>.

<p>jobs are unnecessarily constrained to cores assigned to system instance broker</p><small>Sites may choose to run the system instance broker on a subset of cores, e.g. it may be policy to run all system processes on a constrained list of resources to preserve other resources for user tasks. If this is the case, then the XML loaded by the flux-core `resource` module is also constrained to those same cores, since by default we restrict the hwloc topology to the current cpumask. Since the shell reads the topology XML directly from the `resource` module, it is also restricted to the cpumask of the system instance broker and so on down the line....</small><a href='https://github.com/flux-framework/flux-core/issues/4536' target='_blank'>View Comment</a>