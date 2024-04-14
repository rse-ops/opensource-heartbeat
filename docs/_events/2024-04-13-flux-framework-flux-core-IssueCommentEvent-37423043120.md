---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2024-04-13
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/5883
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/5883' target='_blank'>flux-framework/flux-core#5883</a>.

<small>I didn't find anything wrong with this in testing but I did discover one omission that could be corrected at a later date.  Only the rank 0 broker prohibits peers from reconnecting during cleanup.  The other ranks are still in run state and are perfectly happy to let peers return to service, only to ask them to shutdown once cleanup completes.  It's not wrong, but it seems like wasted effort that we could fix.  Unfortunately it's a little more than I think I can get done today....</small>

<a href='https://github.com/flux-framework/flux-core/pull/5883' target='_blank'>View Comment</a>