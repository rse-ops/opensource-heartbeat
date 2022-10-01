---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-09-30
repo_name: rsmpi/rsmpi
html_url: https://github.com/rsmpi/rsmpi/issues/133
repo_url: https://github.com/rsmpi/rsmpi
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/rsmpi/rsmpi/issues/133' target='_blank'>rsmpi/rsmpi#133</a>.

<small>I'm not concerned about the bandwidth to send the identifier. The complexity is partly that we'd need a collective sense of what a datatype is. They can be created dynamically and independently, and even include absolute addresses (though I think not in rsmpi). The other issue is that memory can reside on GPUs and sometimes the NIC is connected directly to the GPU so it's not easy to get extra bytes into the message payload. This may be a place where we just can't build safe interfaces without significantly deviating from the MPI model. That said, I think the rules of collective programming usually aren't hard to follow once you understand them, in contrast from say, ownership/borrow-checking in languages other than Rust....</small>

<a href='https://github.com/rsmpi/rsmpi/issues/133' target='_blank'>View Comment</a>