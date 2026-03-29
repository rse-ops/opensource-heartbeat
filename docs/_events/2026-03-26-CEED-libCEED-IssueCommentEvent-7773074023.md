---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2026-03-26
repo_name: CEED/libCEED
html_url: https://github.com/CEED/libCEED/issues/1808
repo_url: https://github.com/CEED/libCEED
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/CEED/libCEED/issues/1808' target='_blank'>CEED/libCEED#1808</a>.

<small>In the makefile, we figure that discerning users should set `OPT` themselves. Our default is roughly like CMake's `RelWithDebInfo`, though I think that uses `-O2` by default. I would not be opposed to switching to making the default `-O2` (it's basically a tradeoff of debug sensibility, but you likely still want more aggressive (e.g., associative math) for production runs. (The significance of such flags depends on how the user's qfunctions are written; the library parts of libceed are not so sensitive.)...</small>

<a href='https://github.com/CEED/libCEED/issues/1808' target='_blank'>View Comment</a>