---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2026-11-21
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/5464
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/mfem/mfem/pull/5464' target='_blank'>mfem/mfem#5464</a>.

<small>Good catch @hughcars. There are many cases to fix simultaneously, and the sample runs do not get tested in CI, only in testing after PR approval. It is correct that commit 47297ca10f90cc145e8ed4e4601afd0d84929d3f was added after the fix, when it was realized that the conflict check is only for the case of bisection (scale 0.5). Checking for conflicts with other scales is more complicated and not supported yet, considering the possibility of different scales on neighboring elements. A minimal example not supported is 2 hex elements, with refinements (1) Y with scale 0.5 and (2) XYZ with scale 0.25, where the problem is different scales in the same refinement direction....</small>

<a href='https://github.com/mfem/mfem/pull/5464' target='_blank'>View Comment</a>