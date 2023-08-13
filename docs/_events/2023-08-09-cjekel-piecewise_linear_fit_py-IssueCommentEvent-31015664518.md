---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/13884657?"
user: cjekel
date: 2023-08-09
repo_name: cjekel/piecewise_linear_fit_py
html_url: https://github.com/cjekel/piecewise_linear_fit_py/issues/110
repo_url: https://github.com/cjekel/piecewise_linear_fit_py
---

<a href='https://github.com/cjekel' target='_blank'>cjekel</a> commented on issue <a href='https://github.com/cjekel/piecewise_linear_fit_py/issues/110' target='_blank'>cjekel/piecewise_linear_fit_py#110</a>.

<small>`beta[-1]` can be negative! You just haven't had a curve with a steep enough slope yet at the end. The final slope needs to cancel out the accumulation of all previous slopes. Slopes on the right are the accumulation of all previous beta values (except the y-intercept aka. beta[0])....</small>

<a href='https://github.com/cjekel/piecewise_linear_fit_py/issues/110' target='_blank'>View Comment</a>