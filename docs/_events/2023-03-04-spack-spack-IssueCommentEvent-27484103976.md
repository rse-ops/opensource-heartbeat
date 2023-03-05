---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/299842?"
user: tgamblin
date: 2023-03-04
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/35640
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/tgamblin' target='_blank'>tgamblin</a> commented on issue <a href='https://github.com/spack/spack/pull/35640' target='_blank'>spack/spack#35640</a>.

<small>I think it's really just the stuff in PEP 484 above, with no smart data flow analysis to track the value of the expression.  I suspect it's bc `mypy` is mostly tracking types -- not values -- and they don't want to implement what you'd need to statically analyze the assignment to `is_windows`....</small>

<a href='https://github.com/spack/spack/pull/35640' target='_blank'>View Comment</a>