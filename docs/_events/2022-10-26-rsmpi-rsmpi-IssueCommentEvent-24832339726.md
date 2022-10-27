---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-10-26
repo_name: rsmpi/rsmpi
html_url: https://github.com/rsmpi/rsmpi/issues/136
repo_url: https://github.com/rsmpi/rsmpi
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/rsmpi/rsmpi/issues/136' target='_blank'>rsmpi/rsmpi#136</a>.

<small>I'm sorry, but I don't have capacity to carry on this conversation at this time. You're looking at an associated type. If you have a G1Affine, then [this says](https://docs.rs/blstrs/latest/src/blstrs/g1.rs.html#729) that associated type is [`G1Projective`](https://docs.rs/blstrs/latest/blstrs/struct.G1Projective.html), which is a newtype'd [`blst_p1`](https://docs.rs/blst/0.3.10/blst/struct.blst_p1.html), which again, is a simple struct with array members, and thus can be sent by rsmpi. Please read and adapt the examples. I can't write your code for you....</small>

<a href='https://github.com/rsmpi/rsmpi/issues/136' target='_blank'>View Comment</a>