---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/5669480?"
user: balos1
date: 2022-12-07
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/57
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/balos1' target='_blank'>balos1</a> closed issue <a href='https://github.com/LLNL/sundials/issues/57' target='_blank'>LLNL/sundials#57</a>.

<p>Floating-point underflow in root-finding functions</p><small>Root-finding functions like `arkRootfind` and `cvRootfind` use floating-point multiplication to check whether a sign change has occurred. This is prone to floating-point underflow (e.g. `(-1e-166) * 1e-166` evaluates to 0) which makes the algorithm assume that the sign change was on the wrong sub-interval....</small><a href='https://github.com/LLNL/sundials/issues/57' target='_blank'>View Comment</a>