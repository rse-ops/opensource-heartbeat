---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2025-11-21
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/5054
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/mfem/mfem/pull/5054' target='_blank'>mfem/mfem#5054</a>.

<small>Commit 49cadecc82765de3d928ac5cdafebae921e4acb1 changed `invS` to `CGSolver` and then commit b145001e800a7359f7737844019af5a62063bc05 changed it back to `GMRESSolver`. It seems `CGSolver` is necessary to make the sample runs fast. Is there a good reason to have `GMRESSolver`? I changed it to `CGSolver` and found that the manufactured solution test `nurbs_stokes -m ../../data/square-nurbs.mesh -o 2 -c 3 -sli 100` results in error on the order of 1e-6, which seems accurate enough and is much faster....</small>

<a href='https://github.com/mfem/mfem/pull/5054' target='_blank'>View Comment</a>