---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/10469466?"
user: cjvogl
date: 2024-09-20
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4480
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/cjvogl' target='_blank'>cjvogl</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4480' target='_blank'>mfem/mfem#4480</a>.

<small>Looks like it was a bug: the Picard iteration works fine so long as `KINSolver::EnableAndersonAcc` isn't called.  I'll push a fix momentarily (with a bit of refactoring to avoid combinations of features that cause issues)....</small>

<a href='https://github.com/mfem/mfem/pull/4480' target='_blank'>View Comment</a>