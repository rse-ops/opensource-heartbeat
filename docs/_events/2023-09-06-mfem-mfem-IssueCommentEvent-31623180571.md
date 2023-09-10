---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2023-09-06
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3856
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3856' target='_blank'>mfem/mfem#3856</a>.

<small>Thanks @chakshinglee for finding this issue. Apparently, there were no tests of any kind in MFEM for this case, because all tests are run before a PR is merged. I was not familiar with the case of `element_matrices` being used, and it looks like `element_matrices` is defined only by the function `BilinearForm::ComputeElementMatrices()`, which is only called if the flag `MFEM_USE_LEGACY_OPENMP` is defined. Please correct me if I am missing something. If not, that may explain why this was never caught, that `MFEM_USE_LEGACY_OPENMP` is not tested and is rarely used....</small>

<a href='https://github.com/mfem/mfem/issues/3856' target='_blank'>View Comment</a>