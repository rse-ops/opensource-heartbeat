---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-04-01
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/49698
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/pull/49698' target='_blank'>spack/spack#49698</a>.

<small>It (cmake) does keep them separate, but there are two meaningfully different ways that cmake  hip projects build (not counting just yelling YOLO and pretending `hipcc` will help). The cmake native way, what we usually do at Livermore with BLT these days, uses the actual hip language and as you say adds `-x hip` and uses split flags.  Kokkos, and most things derived from Kokkos, treat everything as C++, use the cmake variables for c++, and manually changes the c++ compiler to a hip compiler and injects the `-x hip` and libraries.  As long as we don't break either of those, and keep commands executing the command that was requested, we should be good....</small>

<a href='https://github.com/spack/spack/pull/49698' target='_blank'>View Comment</a>