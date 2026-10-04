---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/2652545?"
user: milroy
date: 2026-10-02
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1568
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/milroy' target='_blank'>milroy</a> open issue <a href='https://github.com/flux-framework/flux-sched/issues/1568' target='_blank'>flux-framework/flux-sched#1568</a>.

<p>Planner_multi_update() can change planner positions, causing incorrect span updates</p><small>As @zekemorton noted in his review of PR #1540, `planner_multi` stores each multi-span as a vector of per-planner span ids. The vector is indexed by planner position when `planner_multi_add_span()` in the C interface executes. `planner_multi_update()` can change the planner positions. `add_planner()` inserts at the caller's index, `update_planner_index()` moves a planner, and `delete_planners()` compacts the container. Nothing updates the stored vectors....</small><a href='https://github.com/flux-framework/flux-sched/issues/1568' target='_blank'>View Comment</a>