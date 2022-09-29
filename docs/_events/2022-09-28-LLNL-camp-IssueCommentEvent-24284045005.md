---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5669480?"
user: balos1
date: 2022-09-28
repo_name: LLNL/camp
html_url: https://github.com/LLNL/camp/issues/110
repo_url: https://github.com/LLNL/camp
---

<a href='https://github.com/balos1' target='_blank'>balos1</a> commented on issue <a href='https://github.com/LLNL/camp/issues/110' target='_blank'>LLNL/camp#110</a>.

<small>@pelesh  We do not use blt in SUNDIALS, so we run into this issue of the target `cuda_runtime` not being around with camp@2022.03.2 and RAJA@2022.03.1 (this was not a problem with versions before 2022.x.x). For now, I am working around it by creating a target `cuda_runtime` after `find_package(RAJA)` (if the target does not exist, see [here](https://github.com/LLNL/sundials/commit/62609f660cf152779d6538fa224958a17a8a9a2b)). I would think that targets that blt produces should get defined somewhere in the exported `.cmake` files by libraries that use blt (so libraries that do not use blt can find them), so I am hoping once blt refactors the CUDA support we won't need to do this anymore.  ...</small>

<a href='https://github.com/LLNL/camp/issues/110' target='_blank'>View Comment</a>