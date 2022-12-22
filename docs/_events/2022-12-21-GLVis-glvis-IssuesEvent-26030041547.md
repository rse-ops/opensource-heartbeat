---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/1278247?"
user: tzanio
date: 2022-12-21
repo_name: GLVis/glvis
html_url: https://github.com/GLVis/glvis/issues/248
repo_url: https://github.com/GLVis/glvis
---

<a href='https://github.com/tzanio' target='_blank'>tzanio</a> closed issue <a href='https://github.com/GLVis/glvis/issues/248' target='_blank'>GLVis/glvis#248</a>.

<p>Scalar fields with MapType INTEGRAL do not display properly</p><small>The problem is two-fold. First, loading the `GridFunction` in `StreamState` uses `GridFunction::GetNodalValues` which contains an `MFEM_ASSERT` requiring MapType VALUE. Second, the range used in the colorbar is based on minimum and maximum values in the vector of degrees of freedom....</small><a href='https://github.com/GLVis/glvis/issues/248' target='_blank'>View Comment</a>