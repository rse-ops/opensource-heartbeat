---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/987639?"
user: samuelkgutierrez
date: 2025-11-30
repo_name: hpc/quo-vadis
html_url: https://github.com/hpc/quo-vadis/issues/411
repo_url: https://github.com/hpc/quo-vadis
---

<a href='https://github.com/samuelkgutierrez' target='_blank'>samuelkgutierrez</a> closed issue <a href='https://github.com/hpc/quo-vadis/issues/411' target='_blank'>hpc/quo-vadis#411</a>.

<p>qv_scope_create() is broken with QV_SCOPE_FLAG_NO_SMT</p><small>I'm looking into a solution. I've found the problem, but a potential solution may involve maintaining multiple topologies. That is, if we detect the use of QV_SCOPE_FLAG_NO_SMT, we can restrict the topology, but then we can't use that one for other scopes without the SMT flag....</small><a href='https://github.com/hpc/quo-vadis/issues/411' target='_blank'>View Comment</a>