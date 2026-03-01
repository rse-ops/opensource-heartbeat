---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2026-02-24
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/5195
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/mfem/mfem/pull/5195' target='_blank'>mfem/mfem#5195</a>.

<small>@v-dobrev commit afded067a74594bb71520832ae5024f1556cbd75 replaces `absdof`. Thanks for pointing this out. In fespace, `DecodeDof` is more complicated, as it has a version returning a sign. This commit uses `UnsignIndex` for the implementation of the basic `DecodeDof`, but I am keeping `DecodeDof` in fespace as is. An alternative would be to add another version `UnsignIndex(int i, real_t& sign)` to replace `DecodeDof`, but I don't see a need for that in general, outside `FiniteElementSpace`....</small>

<a href='https://github.com/mfem/mfem/pull/5195' target='_blank'>View Comment</a>