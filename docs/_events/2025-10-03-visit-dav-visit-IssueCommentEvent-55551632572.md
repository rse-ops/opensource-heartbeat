---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2025-10-03
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/17308
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/visit-dav/visit/issues/17308' target='_blank'>visit-dav/visit#17308</a>.

<small>I have looked at this a number of different ways. The Mili dataset is a bit unique in that it is a mesh consisting of hex elements (3D), quad elements (2D) and line elements (1D). The stress variable is defined using 6 scalars, `sx`, `sy`, `sz` and `sxy`, `syz` and `sxz`. Its a *symmetric* tensor. And it is *defined* on both the hex (3D) and quad (2D) elements. As an aside, I *never* get a `plot yielded no data warning`.  I printed and queried values using `%16.16g` and everything shows all zeros. When I run with `-debug 5` on the command-line, I see the `vtkMath.cxx:778` spew to `stderr` and in the `.vlogs`. I looked at the `vtkMath.cxx` source code and comments. ...</small>

<a href='https://github.com/visit-dav/visit/issues/17308' target='_blank'>View Comment</a>