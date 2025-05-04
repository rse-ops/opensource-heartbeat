---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2025-05-01
repo_name: CEED/libCEED
html_url: https://github.com/CEED/libCEED/pull/1813
repo_url: https://github.com/CEED/libCEED
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/CEED/libCEED/pull/1813' target='_blank'>CEED/libCEED#1813</a>.

<small>Revisiting this while trying to understand the root issue of weak symbols not working with static linking on MacOS. I don't have a solution there, but I found that `ar crD` doesn't work because Apple `ar` does not support `D` (deterministic), but one can use the environment variable `ZERO_AR_DATE=1`....</small>

<a href='https://github.com/CEED/libCEED/pull/1813' target='_blank'>View Comment</a>