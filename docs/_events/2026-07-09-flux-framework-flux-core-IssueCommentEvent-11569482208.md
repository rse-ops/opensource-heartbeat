---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/56830868?"
user: sam-maloney
date: 2026-07-09
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/7677
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/sam-maloney' target='_blank'>sam-maloney</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/7677' target='_blank'>flux-framework/flux-core#7677</a>.

<small>I would immediately think that `target` should only ever be `0` or `1`, as otherwise the request would skip over intermediate instances, which feels like a violation of the hierarchical model. Certainly for a shrink/partial release, those resources would have to be removed from the resource set of each instance in the hierarchy in any case, and then you have the more philosophical question of what gives a lower level application/instance the right to determine what its parent/ancestor instances do with their resources. I suppose a user might reasonably want a way to indicate that an application is releasing resources which are no longer needed by its own local instance for further workflow steps, but that would be different from the `target` proposed here, as the shrink would still need to be dealt with by the local instance first, it would just be guaranteed to be immediately followed by an equivalent `job_manager.dyn_alloc_request` from the local instance to its immediate parent....</small>

<a href='https://github.com/flux-framework/flux-core/pull/7677' target='_blank'>View Comment</a>