---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2026-08-19
repo_name: flux-framework/flux-coral2
html_url: https://github.com/flux-framework/flux-coral2/issues/496
repo_url: https://github.com/flux-framework/flux-coral2
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> closed issue <a href='https://github.com/flux-framework/flux-coral2/issues/496' target='_blank'>flux-framework/flux-coral2#496</a>.

<p>flux-rabbitmapping double-counts allocations</p><small>`flux rabbitmapping` takes the `.status.capacity` field of `storage` resources and then subtracts `systemstorage` capacity from it to get a baseline free capacity. However, as described in [this issue](https://github.com/DataWorkflowServices/dws/issues/284), `.status.capacity` is actually a measure of free capacity, not total capacity. So Flux double-counts allocations, reducing the capacity that should be considered available to jobs....</small><a href='https://github.com/flux-framework/flux-coral2/issues/496' target='_blank'>View Comment</a>