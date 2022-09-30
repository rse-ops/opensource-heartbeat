---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-09-29
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/4623
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/4623' target='_blank'>flux-framework/flux-core#4623</a>.

<small>There's a special watcher *to watch other handles*, that's the HandleWatcher, so it lets us add a second handle to the current one.  Doing that with a callback that will process its events should let us add the "foreign handle" or what have you and watch it until the future being awaited is fulfilled, then we remove that watcher from the current loop.  There may be more efficient ways to do this, but I'm relatively sure it will work correctly....</small>

<a href='https://github.com/flux-framework/flux-core/pull/4623' target='_blank'>View Comment</a>