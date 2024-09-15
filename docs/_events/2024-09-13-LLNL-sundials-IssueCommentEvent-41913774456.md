---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5669480?"
user: balos1
date: 2024-09-13
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/561
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/balos1' target='_blank'>balos1</a> commented on issue <a href='https://github.com/LLNL/sundials/issues/561' target='_blank'>LLNL/sundials#561</a>.

<small>I dont think this is a bug as much as a mismatch in the Petsc and SUNDIALS configuration. The size/type of `sunindextype` can be changed between 32 and 64-bit with the CMake option `SUNDIALS_INDEX_SIZE`.  `PetscInt` [can also be configured](https://petsc.org/main/manualpages/Sys/PetscInt/#petscint) to be 32 or 64-bit. The libraries should be configured in a compatible way.  ...</small>

<a href='https://github.com/LLNL/sundials/issues/561' target='_blank'>View Comment</a>