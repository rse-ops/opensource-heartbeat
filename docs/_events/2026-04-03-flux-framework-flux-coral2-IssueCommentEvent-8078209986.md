---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2026-04-03
repo_name: flux-framework/flux-coral2
html_url: https://github.com/flux-framework/flux-coral2/issues/466
repo_url: https://github.com/flux-framework/flux-coral2
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> commented on issue <a href='https://github.com/flux-framework/flux-coral2/issues/466' target='_blank'>flux-framework/flux-coral2#466</a>.

<small>Oh ok that's very helpful actually. What's happening is that Flux is trying to watch the `storages` resource in K8s for updates about rabbit status. It asks k8s to only see recent changes, where "recent" is defined by passing in an identifier string grabbed from one of the `storages` resources. However, kubernetes is rejecting the string as being too old--I guess there is a `storage` resource on elcap somewhere that hasn't been updated in a long time. As a fallback, with Kubernetes rejecting the watch request, Flux asks to get the current status of every single rabbit on the system. That takes a long time to process. Then Flux tries to watch changes to the `storages` resources again with a new identifier string (and hopefully a more recent one that kubernetes will accept). But no--for whatever reason, the identifier string is rejected once more, and the cycle begins again. In effect, Flux asks to get the current status of every single rabbit on the system every five seconds. This generates a ton of traffic and log messages....</small>

<a href='https://github.com/flux-framework/flux-coral2/issues/466' target='_blank'>View Comment</a>