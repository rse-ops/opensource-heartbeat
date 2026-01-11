---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/30813018?"
user: btalamini
date: 2026-01-08
repo_name: llnl/smith
html_url: https://github.com/llnl/smith/issues/1517
repo_url: https://github.com/llnl/smith
---

<a href='https://github.com/btalamini' target='_blank'>btalamini</a> open issue <a href='https://github.com/llnl/smith/issues/1517' target='_blank'>llnl/smith#1517</a>.

<p>Avoid copying stiffness matrix for adjoint solves</p><small>We currently ask the stiffness matrix for its transpose, which allocates another sparse matrix. Now that we have a differentiable solver abstraction, we could have the adjoint solve use the action of the transpose, say using the MFEM `TransposeOperator`....</small><a href='https://github.com/llnl/smith/issues/1517' target='_blank'>View Comment</a>