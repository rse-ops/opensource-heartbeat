---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2026-04-24
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/5313
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/mfem/mfem/issues/5313' target='_blank'>mfem/mfem#5313</a>.

<small>As @v-dobrev mentioned, `mesh-explorer` has features to help refine (uniformly) and convert the mesh. If you would like more control over refinement, `Mesh::KnotInsert` gives you complete control over the number of elements and their spacing, for each `KnotVector`. If you would like to use lower than 4th-order, it would be best to refine the mesh fully with order 4 and then convert to lower order (e.g. `mesh-explorer` option 'c')....</small>

<a href='https://github.com/mfem/mfem/issues/5313' target='_blank'>View Comment</a>