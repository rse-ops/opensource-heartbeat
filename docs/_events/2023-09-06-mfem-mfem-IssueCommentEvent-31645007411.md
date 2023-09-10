---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/18635640?"
user: chakshinglee
date: 2023-09-06
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3856
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/chakshinglee' target='_blank'>chakshinglee</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3856' target='_blank'>mfem/mfem#3856</a>.

<small>@dylan-copeland thanks for the feedback! Just to give some context: we are implementing some solvers that exploit the element matrices, and we call `BilinearForm::ComputeElementMatrices()` so that the matrices can be stored and extracted later (without computing them again)....</small>

<a href='https://github.com/mfem/mfem/issues/3856' target='_blank'>View Comment</a>