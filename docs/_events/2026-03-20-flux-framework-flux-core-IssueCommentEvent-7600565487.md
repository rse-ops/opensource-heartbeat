---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2026-03-20
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/7451
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/7451' target='_blank'>flux-framework/flux-core#7451</a>.

<small>I just finally got time to actually read this over. This is a massively more complicated scheduler setup than I expected from the "toy" designation. It's a very nice addition, especially as a way to let people experiment with new custom schedulers.  I'm a bit tempted to make a few adjustments to this to make it work more the way qmanager does from a progress and behavior perspective, it might actually not be all that much of a lift to _replace_ qmanager with a reworked version of the backfill class here.  We'd have to do some performance tests and similar, but I'm sorely tempted to give it a shot, especially given some of the features we've been discussing for that recently the flexibility would be nice, and it isn't a compute-bound service either.  Do you think we could find some time to chat over this next week @garlick? ...</small>

<a href='https://github.com/flux-framework/flux-core/pull/7451' target='_blank'>View Comment</a>