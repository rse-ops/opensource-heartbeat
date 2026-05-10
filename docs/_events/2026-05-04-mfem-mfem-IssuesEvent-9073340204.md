---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/2072964?"
user: BradWhitlock
date: 2026-05-04
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/5321
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/BradWhitlock' target='_blank'>BradWhitlock</a> open issue <a href='https://github.com/mfem/mfem/issues/5321' target='_blank'>mfem/mfem#5321</a>.

<p>MFEM appears to give incorrect quadrature-point coordinates for some custom tensor-product quadrature rules when the number of points differs by logical direction, like 5 x 3 in 2D or 5 x 3 x 2 in 3D.</p><small>  - If I build a custom tensor-product `IntegrationRule` from unequal 1D rules and use it with `Mesh::GetGeometricFactors(..., COORDINATES)` on a curved quad/hex mesh, the physical quadrature-point locations can...</small><a href='https://github.com/mfem/mfem/issues/5321' target='_blank'>View Comment</a>