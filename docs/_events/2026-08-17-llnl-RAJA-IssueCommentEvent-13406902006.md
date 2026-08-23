---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/6393677?"
user: adayton1
date: 2026-08-17
repo_name: llnl/RAJA
html_url: https://github.com/llnl/RAJA/pull/1915
repo_url: https://github.com/llnl/RAJA
---

<a href='https://github.com/adayton1' target='_blank'>adayton1</a> commented on issue <a href='https://github.com/llnl/RAJA/pull/1915' target='_blank'>llnl/RAJA#1915</a>.

<small>> > @MrBurmark @adayton1 I assume that SubViews can be 0D in certain cases where the slice(s) reduce the dimension to a scalar. This leads to compiler errors on Windows (see failing CI) because camp array stores a C-style array of size 0. My thoughts are to either disallow 0D SubViews or add a specialization of camp array for a 0-sized array. My preference is the latter because std::array can be zero-sized, so this addition would make camp::array be more consistent with std::array. Any thoughts?...</small>

<a href='https://github.com/llnl/RAJA/pull/1915' target='_blank'>View Comment</a>