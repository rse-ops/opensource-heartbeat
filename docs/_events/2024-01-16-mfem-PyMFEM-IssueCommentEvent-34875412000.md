---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2024-01-16
repo_name: mfem/PyMFEM
html_url: https://github.com/mfem/PyMFEM/issues/200
repo_url: https://github.com/mfem/PyMFEM
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/PyMFEM/issues/200' target='_blank'>mfem/PyMFEM#200</a>.

<small>Good find @XuliaDS! We should probably add that function, `SaveLinearGridFunctionVTK` from https://github.com/mfem/mfem/issues/1398#issuecomment-610031344, to the library as `GridFunction::SaveVTK(std::ostream &out, const std::string &field_name)`. @pazner, what do you think? Also, maybe we can support quadratic H1 spaces too, since `Mesh::PrintVTK` supports quadratic meshes?...</small>

<a href='https://github.com/mfem/PyMFEM/issues/200' target='_blank'>View Comment</a>