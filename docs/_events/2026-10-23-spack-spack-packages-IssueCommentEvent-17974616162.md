---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2026-10-23
repo_name: spack/spack-packages
html_url: https://github.com/spack/spack-packages/pull/6741
repo_url: https://github.com/spack/spack-packages
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/spack/spack-packages/pull/6741' target='_blank'>spack/spack-packages#6741</a>.

<small>@adrienbernede, I see that the build with Intel LLVM failed in the pipeline you linked -- this may be due to the following issue: https://github.com/mfem/mfem/issues/4768. Simply put, we recommend using `-O2 -fp-speculation=safe` with the Intel LLVM compiler to build MFEM....</small>

<a href='https://github.com/spack/spack-packages/pull/6741' target='_blank'>View Comment</a>