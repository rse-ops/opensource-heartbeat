---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2024-09-13
repo_name: CEED/libCEED
html_url: https://github.com/CEED/libCEED/issues/1662
repo_url: https://github.com/CEED/libCEED
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/CEED/libCEED/issues/1662' target='_blank'>CEED/libCEED#1662</a>.

<small>Note that the ordering (with the innermost index over points, which may span a batch of elements) is due to memory coalescing and the way SIMT vectorizes, as well as the way CPU SIMD instructions work. If you change it, the compiler and hardware would have to do lots of transposition, and in many cases would result in quite poor code....</small>

<a href='https://github.com/CEED/libCEED/issues/1662' target='_blank'>View Comment</a>