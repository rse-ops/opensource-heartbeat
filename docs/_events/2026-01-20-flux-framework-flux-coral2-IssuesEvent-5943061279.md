---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2026-01-20
repo_name: flux-framework/flux-coral2
html_url: https://github.com/flux-framework/flux-coral2/issues/444
repo_url: https://github.com/flux-framework/flux-coral2
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> closed issue <a href='https://github.com/flux-framework/flux-coral2/issues/444' target='_blank'>flux-framework/flux-coral2#444</a>.

<p>CRD version tolerance</p><small>Problem: software that interacts with DWS software uses a fixed API version for kubernetes CRDs. Unfortunately, that forces administrators to update the flux-coral2 RPM and DWS software in sync, and if the versions are not compatible the whole ecosystem breaks. Typically this is not as much of an issue because the DWS software tolerates Flux requesting an older API version, so DWS can be updated without Flux. However, sometimes it might be useful to have Flux be updated without updating DWS, which would mean Flux asking DWS about API versions that it thinks do not exist....</small><a href='https://github.com/flux-framework/flux-coral2/issues/444' target='_blank'>View Comment</a>