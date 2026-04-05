---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2026-04-02
repo_name: llnl/RAJA
html_url: https://github.com/llnl/RAJA/pull/2009
repo_url: https://github.com/llnl/RAJA
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/llnl/RAJA/pull/2009' target='_blank'>llnl/RAJA#2009</a>.

<small>As a stylistic note, we do this in OpenMP with `single` if the other threads should wait, or with `masked` or the deprecated `master` if they shouldn't, while `once` is used by C++, C, and posix to mean "run exactly one time, no matter how many threads encounter this, and block all encountering threads until that one run is done"....</small>

<a href='https://github.com/llnl/RAJA/pull/2009' target='_blank'>View Comment</a>