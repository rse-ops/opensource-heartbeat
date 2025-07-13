---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/15018133?"
user: gardner48
date: 2025-07-12
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/702
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/gardner48' target='_blank'>gardner48</a> commented on issue <a href='https://github.com/LLNL/sundials/issues/702' target='_blank'>LLNL/sundials#702</a>.

<small>@emprice Thanks for reporting this problem. I've modified one of our examples using inequality constraints and was able to reproduce similar behavior where the step size is increased rather than cut when a constraint violation is found. This occurs when the predictor and corrector both produce states that do not satisfy the inequality constraint. In this case the computation used to estimate the step size needed to satisfy the constraint is invalid. There are a couple ways to address this. I'll discuss this we the rest of a team and update this issue when I've added a fix....</small>

<a href='https://github.com/LLNL/sundials/issues/702' target='_blank'>View Comment</a>