---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2025-10-25
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/5085
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/pull/5085' target='_blank'>mfem/mfem#5085</a>.

<small>Some thoughts: some of the methods in `ARKStepODE` will be common with other similar classes. How do you envision avoiding repeated definitions? Also, when you inherit from both `TimeDependentOperator` and `ARKStepODE`, you get `Mult` from both and you have `Width`/`Height` (from the former) and `Size` from the latter which is not ideal....</small>

<a href='https://github.com/mfem/mfem/pull/5085' target='_blank'>View Comment</a>