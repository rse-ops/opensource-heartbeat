---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-06-02
repo_name: dealii/dealii
html_url: https://github.com/dealii/dealii/pull/15271
repo_url: https://github.com/dealii/dealii
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/dealii/dealii/pull/15271' target='_blank'>dealii/dealii#15271</a>.

<small>PETSc evaluates residuals before Jacobians (indeed, some users tuck Jacobian evaluation into each residual, though that's not an optimization in the presence of a line search). There is `SNESSetJacobianDomainError`. Some SNES implementations have distinct handling of `snes->domainerror` so I'd encourage using the interfaces rather than raw `VecSetInf`....</small>

<a href='https://github.com/dealii/dealii/pull/15271' target='_blank'>View Comment</a>