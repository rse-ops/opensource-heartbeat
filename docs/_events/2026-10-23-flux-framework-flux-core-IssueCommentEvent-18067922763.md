---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2026-10-23
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/pull/7856
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-core/pull/7856' target='_blank'>flux-framework/flux-core#7856</a>.

<small>Ah, linear search with glob matching.   I did not have that in mind.  Well, on a given shell the number of jobdict gets and puts (which would be plugstack calls from pmi to jobdict) would be proportional to the number of MPI ranks.  I had claude quickly do a microbenchmark with about the same number of registered callbacks as the shell and it came out about 5000x slower than a function call but still 1-2 usec per call.   So we're probably in the 1-2 msec range for a large job.  Not sure that's worth optimizing, although it would be easy to just expose some local functions.  Thoughts?...</small>

<a href='https://github.com/flux-framework/flux-core/pull/7856' target='_blank'>View Comment</a>