---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2025-08-01
repo_name: flux-framework/flux-coral2
html_url: https://github.com/flux-framework/flux-coral2/issues/379
repo_url: https://github.com/flux-framework/flux-coral2
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> commented on issue <a href='https://github.com/flux-framework/flux-coral2/issues/379' target='_blank'>flux-framework/flux-coral2#379</a>.

<small>I think I understand now. As can be seen in the eventlog, Flux was restarted while the job was in the queue, so the plugin was reloaded. The exception callback in the jobtap plugin is only triggered if the plugin has subscribed to events for the job, but the call to `flux_jobtap_job_subscribe()` is only done in the callback for the `SUBMIT` state. (See [here](https://github.com/flux-framework/flux-coral2/blob/4be816f25660883791c3bc8af3dd165c91ab30ad/src/job-manager/plugins/dws-jobtap.c#L199).) So the exception callback was never invoked and the prolog was never removed....</small>

<a href='https://github.com/flux-framework/flux-coral2/issues/379' target='_blank'>View Comment</a>