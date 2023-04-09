---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/17843342?"
user: vladotomov
date: 2023-04-05
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3584
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/vladotomov' target='_blank'>vladotomov</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3584' target='_blank'>mfem/mfem#3584</a>.

<small>If only the edge node coordinates are needed, you can probably get something through `Mesh::GetBdrElementEdges()`, then `FiniiteElementSpace::GetEdgeDofs()`, and then get the values from the `Mesh::Nodes` function that stores the coordinates....</small>

<a href='https://github.com/mfem/mfem/issues/3584' target='_blank'>View Comment</a>