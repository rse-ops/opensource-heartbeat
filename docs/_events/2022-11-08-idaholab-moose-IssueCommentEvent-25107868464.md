---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-11-08
repo_name: idaholab/moose
html_url: https://github.com/idaholab/moose/pull/22054
repo_url: https://github.com/idaholab/moose
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/idaholab/moose/pull/22054' target='_blank'>idaholab/moose#22054</a>.

<small>@lindsayad Factorization should be deterministic so I would not expect a discrepancy. Is there a qualitative difference between PETSc's default solver and an external solver (like `-pc_factor_mat_solver_type umfpack`)? (Umfpack will be more efficient, but do the two "identical" matrices factor to use the same amount of memory?) Can you reduce and share `-ksp_view` output (which reports fill in the factorization)....</small>

<a href='https://github.com/idaholab/moose/pull/22054' target='_blank'>View Comment</a>