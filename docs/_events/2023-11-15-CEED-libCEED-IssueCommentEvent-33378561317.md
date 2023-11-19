---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-11-15
repo_name: CEED/libCEED
html_url: https://github.com/CEED/libCEED/issues/1395
repo_url: https://github.com/CEED/libCEED
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/CEED/libCEED/issues/1395' target='_blank'>CEED/libCEED#1395</a>.

<small>In order to avoid warp divergence, we want everything in a thread block to have homogeneous properties. I could imagine creating fused kernels for composite operators that carefully pad the iteration space to ensure this alignment, but I'm not aware of performance benefit for doing that. I realize that putting integer flags into floating point values isn't very satisfying, but it is exact (for a big range of integers) and avoids internal complexity that I'm not convinced pays off....</small>

<a href='https://github.com/CEED/libCEED/issues/1395' target='_blank'>View Comment</a>