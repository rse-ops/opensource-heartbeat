---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2024-02-22
repo_name: RDycore/RDycore
html_url: https://github.com/RDycore/RDycore/pull/133
repo_url: https://github.com/RDycore/RDycore
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/RDycore/RDycore/pull/133' target='_blank'>RDycore/RDycore#133</a>.

<small>First, we can build a matrix using coloring (`-snes_fd_color`; no code). We can also compare fully matrix-free. We'll likely want to assemble a point-block diagonal (for `-pc_type pbjacobi` or `vpbjacobi`), but that can be approximate. I don't envision assembling the complete Jacobian, certainly not for the current operator (versus a lagged one used to build a lagged preconditioner). In any case, libCEED/PETSc have an interface to do this when we write the matrix-free action in a qfunction. That matrix-free action could be computed using Enzyme....</small>

<a href='https://github.com/RDycore/RDycore/pull/133' target='_blank'>View Comment</a>