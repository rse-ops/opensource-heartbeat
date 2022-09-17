---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5669480?"
user: balos1
date: 2022-09-17
repo_name: xiaoyeli/superlu_dist
html_url: https://github.com/xiaoyeli/superlu_dist/issues/94
repo_url: https://github.com/xiaoyeli/superlu_dist
---

<a href='https://github.com/balos1' target='_blank'>balos1</a> commented on issue <a href='https://github.com/xiaoyeli/superlu_dist/issues/94' target='_blank'>xiaoyeli/superlu_dist#94</a>.

<small>I came across this same issue. For me, the problem was that the `CMAKE_CUDA_ARCHITECUTRES` variable was set too low. Based on the output from running CMake to configure SuperLU, it seemed like the right CUDA arch was detected, but the `CMAKE_CUDA_ARCHITECUTRES` was not getting set accordingly.  When I explicitly set `CMAKE_CUDA_ARCHITECUTRES` to 60 or higher (`atomicAdd` with doubles requires compute capability 6.0 or higher) then everything works as expected....</small>

<a href='https://github.com/xiaoyeli/superlu_dist/issues/94' target='_blank'>View Comment</a>