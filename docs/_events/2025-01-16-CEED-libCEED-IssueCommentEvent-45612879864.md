---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2025-01-16
repo_name: CEED/libCEED
html_url: https://github.com/CEED/libCEED/issues/1728
repo_url: https://github.com/CEED/libCEED
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/CEED/libCEED/issues/1728' target='_blank'>CEED/libCEED#1728</a>.

<small>I'm not really following the need for `vec->CopyArray`. Where would that memory come from? Is there a reason not to wrap it in a `CeedVector` and then `CeedVectorCopy` instead of introducing a new way to use a raw pointer (without specifying its length, but tacitly promising that it's long enough)?...</small>

<a href='https://github.com/CEED/libCEED/issues/1728' target='_blank'>View Comment</a>