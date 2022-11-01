---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/10790104?"
user: daboehme
date: 2022-10-31
repo_name: LLNL/Caliper
html_url: https://github.com/LLNL/Caliper/pull/446
repo_url: https://github.com/LLNL/Caliper
---

<a href='https://github.com/daboehme' target='_blank'>daboehme</a> commented on issue <a href='https://github.com/LLNL/Caliper/pull/446' target='_blank'>LLNL/Caliper#446</a>.

<small>Hi @jrmadsen , thanks for the comments. The problem seems to be calling std::forward in the loop, which seems to destroy any argument passed in as rvalue reference after the first iteration. I ran into this when passing a lambda as an argument for the callback function, when I defined the lambda directly in the function call. The example below demonstrates this. Removing the std::forward (or avoid passing rvalue references altogether) fixes it. I guess perfect forwarding the same thing multiple times as I do in the callback loop is undefined or just plain wrong. I get that copying might have its problems too, but it does seems to work....</small>

<a href='https://github.com/LLNL/Caliper/pull/446' target='_blank'>View Comment</a>