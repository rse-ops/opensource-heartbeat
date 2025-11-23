---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2072964?"
user: BradWhitlock
date: 2025-11-18
repo_name: LLNL/axom
html_url: https://github.com/LLNL/axom/issues/1724
repo_url: https://github.com/LLNL/axom
---

<a href='https://github.com/BradWhitlock' target='_blank'>BradWhitlock</a> commented on issue <a href='https://github.com/LLNL/axom/issues/1724' target='_blank'>LLNL/axom#1724</a>.

<small>@rhornung67 - I agree this is probably rare. Calling the Umpire function to make the resource manager is a more explicit workaround. Still, I ran into it because Umpire is not front and center in Axom so I did not realize I might run into problems calling `axom::copy` from an OpenMP loop. I thought I'd note the issue. I could also switch to `memcpy()` in this instance....</small>

<a href='https://github.com/LLNL/axom/issues/1724' target='_blank'>View Comment</a>