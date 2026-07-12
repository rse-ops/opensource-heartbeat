---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5412886?"
user: jandrej
date: 2026-07-07
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/5350
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/jandrej' target='_blank'>jandrej</a> commented on issue <a href='https://github.com/mfem/mfem/pull/5350' target='_blank'>mfem/mfem#5350</a>.

<small>> This is an interesting PR but I think it requires some discussion with the MFEM team at large. One of the basic tenets of the finite element method is that there is one mesh which is subdivided into elements on which we represent our fields. This PR relaxes this requirement for the special case where one mesh is a sub-mesh of another. Another alternative would be to compute bilinear forms on the primary and sub-mesh separately and combine these separate operators into a block system using coupling operators to define the mapping between finite element spaces....</small>

<a href='https://github.com/mfem/mfem/pull/5350' target='_blank'>View Comment</a>