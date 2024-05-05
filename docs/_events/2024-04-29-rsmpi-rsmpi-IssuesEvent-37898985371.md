---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2024-04-29
repo_name: rsmpi/rsmpi
html_url: https://github.com/rsmpi/rsmpi/issues/182
repo_url: https://github.com/rsmpi/rsmpi
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> closed issue <a href='https://github.com/rsmpi/rsmpi/issues/182' target='_blank'>rsmpi/rsmpi#182</a>.

<p>Should ready send be unsafe?</p><small>Ready send is quite unsafe, as I've documented in https://github.com/rsmpi/rsmpi/commit/1e5eeabc7f2b7f55976d3bc8df0867a229d03425 after someone accidentally misused it. @jtronge @hppritcha :wave: Do you feel like there is any way to make a safe ready send (and would that be worth it)? My biggest concern here is that while misuse can often be reported by MPI, it is not even deterministically knowable whether the a receive has been posted before a ready send is initiated. I think there are some symbolic execution/formal methods techniques that can be applied to this problem, but I don't see a way to get that sort of thing into the Rust type system. Also, I think ready-send is quite a niche that we shouldn't be encouraging users to use. Shall I make the ready send interfaces `unsafe` for mpi-0.8?...</small><a href='https://github.com/rsmpi/rsmpi/issues/182' target='_blank'>View Comment</a>