---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-10-07
repo_name: rsmpi/rsmpi
html_url: https://github.com/rsmpi/rsmpi/issues/133
repo_url: https://github.com/rsmpi/rsmpi
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/rsmpi/rsmpi/issues/133' target='_blank'>rsmpi/rsmpi#133</a>.

<small>Consider a halo region for a PDE solver. You can use a derived type to offload packing/unpacking, but the send will be from the "interior" of the owner domain and received into the halo region, so those will be different derived types. You could say that because MPI implementations generally aren't very optimized in their packing, callers should always pack explicitly, but that either requires extra kernel launches (on GPUs) or potentially poor interaction with threads on the CPU side. We could eschew the feature from Rust, but that's taking an opinionated stand rather than exposing MPI functionality....</small>

<a href='https://github.com/rsmpi/rsmpi/issues/133' target='_blank'>View Comment</a>