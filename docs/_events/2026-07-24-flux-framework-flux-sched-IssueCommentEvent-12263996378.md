---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2026-07-24
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/pull/1534
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/pull/1534' target='_blank'>flux-framework/flux-sched#1534</a>.

<small>> Note: it is difficult to change the phrasing of statements like `opt_p.value_or (null_planner)` because none of `boost::optional`'s operators cleanly express "empty or populated with nullptr" or the inverse in a single statement (`opt_x == boost::optional (nullptr)` returns false when empty and true when null), and `try_at` only returns references but `boost::optional` cannot be initialized with an rvalue reference (see [Optional references](https://www.boost.org/doc/libs/1_82_0/libs/optional/doc/html/boost_optional/tutorial/optional_references.html))....</small>

<a href='https://github.com/flux-framework/flux-sched/pull/1534' target='_blank'>View Comment</a>