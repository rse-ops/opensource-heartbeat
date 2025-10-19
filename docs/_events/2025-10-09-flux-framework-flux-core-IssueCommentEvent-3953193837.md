---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-10-09
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/7130
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/7130' target='_blank'>flux-framework/flux-core#7130</a>.

<small>That sounds right.  The fluxion code that reads from these always uses the max currently though, and somewhat relies on there being an upper bound.  We can certainly make the max optional, but the effect will be that the min will become the max until we have time to work through how to handle unbounded requests....</small>

<a href='https://github.com/flux-framework/flux-core/pull/7130' target='_blank'>View Comment</a>