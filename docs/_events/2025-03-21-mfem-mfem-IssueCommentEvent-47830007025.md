---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2025-03-21
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4756
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4756' target='_blank'>mfem/mfem#4756</a>.

<small>Hi @kogtenev, thanks for your question. In general, for different types of spaces, conformity in the `FiniteElementSpace` is enforced by a conforming prolongation operator that maps from true DOFs to the full DOFs taken from all elements of their respective orders. The prolongation is done, regardless of the space type, by constraining high-order DOFs on shared edges and faces to interpolate the lowest order on the edge/face. I have worked on H1 spaces but not Nedelec spaces, in the context of variable order, so maybe there are some issues specific to Nedelec spaces that someone else can comment on, but I think this basic explanation is valid for all types of spaces. In particular, conformity should mean that tangential components are continuous, and the true DOFs are those of the lowest order on each entity (edge/face)....</small>

<a href='https://github.com/mfem/mfem/issues/4756' target='_blank'>View Comment</a>