---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-10-26
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4724
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/trws' target='_blank'>trws</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/4724' target='_blank'>flux-framework/flux-core#4724</a>.

<p>GPU oversubscription with no GPU requested</p><small>This example comes from @gyllenhaal1.  The thread distribution is at least for now what was requested, but there are no GPUs requested (unless we treat this as exclusive) and even if there were somehow all tasks receive GPU 1, not zero, not all of them, 1.  This hurts my brain thinking about how precisely this could have happened honestly, it's like getting a segfault on ptr==7.  Either way, something funny is going on that we probably want to clean up....</small><a href='https://github.com/flux-framework/flux-core/issues/4724' target='_blank'>View Comment</a>