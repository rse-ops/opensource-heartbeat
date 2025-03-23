---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2025-03-21
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/pull/20321
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/visit-dav/visit/pull/20321' target='_blank'>visit-dav/visit#20321</a>.

<small>I've discovered from other changes I need to make here. `isinstance(x, str)` was generating a `ValueError` exception due to no `__class__` attribute. I think the solution is that we need to switch from `getattr`/`setattr` to `getattro`/`setattro`. I am testing on one object and it seems to be behaving better....</small>

<a href='https://github.com/visit-dav/visit/pull/20321' target='_blank'>View Comment</a>