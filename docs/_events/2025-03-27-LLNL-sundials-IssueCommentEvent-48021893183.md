---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5669480?"
user: balos1
date: 2025-03-27
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/682
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/balos1' target='_blank'>balos1</a> commented on issue <a href='https://github.com/LLNL/sundials/issues/682' target='_blank'>LLNL/sundials#682</a>.

<small>When you run CMake [`sundials_config.in](https://github.com/LLNL/sundials/blob/main/include/sundials/sundials_config.in)` is processed into `builddir/include/sundials_config.h`, which is then installed in `instdir/include/sundials/sundials_config.h`.  The processed `sundials_config.h` should not have any `#cmakedefine` statements in it, so It appears that you are somehow including a `sundials_config.h` that has not been processed by CMake....</small>

<a href='https://github.com/LLNL/sundials/issues/682' target='_blank'>View Comment</a>