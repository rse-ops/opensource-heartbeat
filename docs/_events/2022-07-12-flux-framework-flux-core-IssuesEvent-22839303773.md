---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/20131404?"
user: cmoussa1
date: 2022-07-12
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4405
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/cmoussa1' target='_blank'>cmoussa1</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/4405' target='_blank'>flux-framework/flux-core#4405</a>.

<p>job-manager: dependency does not get added until after job exits job.state.depend</p><small>After updating my flux-core Docker images to the latest versions of flux-core, I noticed some of my sharness tests failing with my priority plugin, specifically the tests that deal with `max_running_jobs` limits. Currently, this limit is enforced by adding a job dependency to the job in `job.state.depend`. After updating flux-core, however, it seems the dependency does not get added until after the job exits `job.state.depend` and enters SCHED state. Here's a specific case I ran into:...</small><a href='https://github.com/flux-framework/flux-core/issues/4405' target='_blank'>View Comment</a>