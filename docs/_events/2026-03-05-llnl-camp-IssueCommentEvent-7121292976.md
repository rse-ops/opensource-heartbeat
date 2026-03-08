---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/6393677?"
user: adayton1
date: 2026-03-05
repo_name: llnl/camp
html_url: https://github.com/llnl/camp/pull/194
repo_url: https://github.com/llnl/camp
---

<a href='https://github.com/adayton1' target='_blank'>adayton1</a> commented on issue <a href='https://github.com/llnl/camp/pull/194' target='_blank'>llnl/camp#194</a>.

<small>I'm actually wondering if we should remove camp::array since we should be able to use std::array in device code now that we require c++17 (almost everything in std::array is constexpr in c++17, and everything is constexpr in c++20). With nvcc you have to supply the `--expt-relaxed-constexpr` flag, which will make all constexpr function `__host__ __device__`, but with amdclang, constexpr automatically implies `__host__ __device__`....</small>

<a href='https://github.com/llnl/camp/pull/194' target='_blank'>View Comment</a>