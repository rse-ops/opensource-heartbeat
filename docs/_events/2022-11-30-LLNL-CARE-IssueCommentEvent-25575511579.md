---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/6393677?"
user: adayton1
date: 2022-11-30
repo_name: LLNL/CARE
html_url: https://github.com/LLNL/CARE/pull/208
repo_url: https://github.com/LLNL/CARE
---

<a href='https://github.com/adayton1' target='_blank'>adayton1</a> commented on issue <a href='https://github.com/LLNL/CARE/pull/208' target='_blank'>LLNL/CARE#208</a>.

<small>@robinson96, looks like the tests failed because CARE is still on C++11 by default and you used std::remove_const_t which is in C++14. Can you bump the default to C++14 (I think it's BLT_CXX_STD in CMakeLists.txt)? ...</small>

<a href='https://github.com/LLNL/CARE/pull/208' target='_blank'>View Comment</a>