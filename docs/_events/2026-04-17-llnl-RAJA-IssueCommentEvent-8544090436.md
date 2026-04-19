---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4537104?"
user: artv3
date: 2026-04-17
repo_name: llnl/RAJA
html_url: https://github.com/llnl/RAJA/pull/2006
repo_url: https://github.com/llnl/RAJA
---

<a href='https://github.com/artv3' target='_blank'>artv3</a> commented on issue <a href='https://github.com/llnl/RAJA/pull/2006' target='_blank'>llnl/RAJA#2006</a>.

<small>> I played with making a range type that could have any of begin, end, and stride be runtime or compile time constants. Is that something that you are interested in @artv3. Right now you construct the range in the lambda so the compiler knows that begin is a constant 0, but if you constructed the range outside of the lambda and captured it then the compiler would not know that begin is a constant. If you had a range type that could have any of the parameters be constant or runtime could fix that....</small>

<a href='https://github.com/llnl/RAJA/pull/2006' target='_blank'>View Comment</a>