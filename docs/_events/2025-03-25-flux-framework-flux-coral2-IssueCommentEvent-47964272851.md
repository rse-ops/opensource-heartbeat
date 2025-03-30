---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-03-25
repo_name: flux-framework/flux-coral2
html_url: https://github.com/flux-framework/flux-coral2/issues/295
repo_url: https://github.com/flux-framework/flux-coral2
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-coral2/issues/295' target='_blank'>flux-framework/flux-coral2#295</a>.

<small>That's fair, I suppose I was thinking of it as a local event of a sort I'm not sure we even support, get notified of a load or unload of modules on the current broker.  We could certainly add an event for "load complete" or similar, it would still leave it somewhat racy in that we might have started before the properties are updated but should at least be after all basic setup is complete....</small>

<a href='https://github.com/flux-framework/flux-coral2/issues/295' target='_blank'>View Comment</a>