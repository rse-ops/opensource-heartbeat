---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2025-11-30
repo_name: CEED/libCEED
html_url: https://github.com/CEED/libCEED/issues/1905
repo_url: https://github.com/CEED/libCEED
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/CEED/libCEED/issues/1905' target='_blank'>CEED/libCEED#1905</a>.

<small>It would depend on the loop body. For example, if it calls functions that don't vectorize (we did the series work with `log1p` because it doesn't vectorize in common implementations) or has branches that are unsafe/hard for the compiler to transform into masked vector arithmetic....</small>

<a href='https://github.com/CEED/libCEED/issues/1905' target='_blank'>View Comment</a>