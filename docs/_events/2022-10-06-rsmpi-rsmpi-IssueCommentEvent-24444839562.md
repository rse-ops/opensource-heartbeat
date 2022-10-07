---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-10-06
repo_name: rsmpi/rsmpi
html_url: https://github.com/rsmpi/rsmpi/issues/133
repo_url: https://github.com/rsmpi/rsmpi
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/rsmpi/rsmpi/issues/133' target='_blank'>rsmpi/rsmpi#133</a>.

<small>As far as the MPI standard is concerned, types need only be compatible. So you can send an array of count=6 doubles and receive count=2 copies of a derived type with 3 doubles. Indeed, the send and receive types could each use absolute addresses and be non-contiguous. Also note that one can post a receive that is bigger than the incoming message (and use status to determine how much was actually received). So creating a hash or other compact encoding that can be checked is more subtle than it appears at first glance. If we want rsmpi to be sound in the way Rust users expect, we may have to make point-to-point unsafe, and make sure we're building good tools for higher level abstractions (mostly collectives, perhaps nonblocking)....</small>

<a href='https://github.com/rsmpi/rsmpi/issues/133' target='_blank'>View Comment</a>