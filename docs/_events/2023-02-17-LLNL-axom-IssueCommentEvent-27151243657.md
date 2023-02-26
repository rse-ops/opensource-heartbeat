---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2072964?"
user: BradWhitlock
date: 2023-02-17
repo_name: LLNL/axom
html_url: https://github.com/LLNL/axom/issues/994
repo_url: https://github.com/LLNL/axom
---

<a href='https://github.com/BradWhitlock' target='_blank'>BradWhitlock</a> commented on issue <a href='https://github.com/LLNL/axom/issues/994' target='_blank'>LLNL/axom#994</a>.

<small>I added some code in C2CReader that compute derivatives and curvature for a spline. Next, I prototyped a non-uniform method of point generation that computes a curvature range for a span and then samples it for target curvature values whose "u" value is then computed. It's sampling the curvature range with a "sigmoid-like" curve that highlights low curvature a little, middle values some, and higher curvature values more. The u values are fed back into the interpolator to generate points. We're still making a user-specified number of segments per knot span as before. For small numbers of segments, prioritizing point placement using the curvature seems good. At least, it makes curves appear with smaller numbers of segments. I'm still looking at options and I need to hook up this method to some metrics to see whether it improves accuracy....</small>

<a href='https://github.com/LLNL/axom/issues/994' target='_blank'>View Comment</a>