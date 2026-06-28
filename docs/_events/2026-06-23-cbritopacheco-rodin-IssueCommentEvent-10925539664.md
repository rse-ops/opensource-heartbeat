---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/6352283?"
user: cbritopacheco
date: 2026-06-23
repo_name: cbritopacheco/rodin
html_url: https://github.com/cbritopacheco/rodin/pull/302
repo_url: https://github.com/cbritopacheco/rodin
---

<a href='https://github.com/cbritopacheco' target='_blank'>cbritopacheco</a> commented on issue <a href='https://github.com/cbritopacheco/rodin/pull/302' target='_blank'>cbritopacheco/rodin#302</a>.

<small>Closing: this was an optimization/uniformity change (MatAXPY preassembled-merge fast path + OpenMP buffer hoisting), not a bugfix. The fast path regressed value-Dirichlet assembly on PETSc 3.19 (MatZeroRowsColumns missing-diagonal). Not worth the risk 