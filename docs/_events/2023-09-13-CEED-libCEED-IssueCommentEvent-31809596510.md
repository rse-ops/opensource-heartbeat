---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-09-13
repo_name: CEED/libCEED
html_url: https://github.com/CEED/libCEED/issues/1328
repo_url: https://github.com/CEED/libCEED
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/CEED/libCEED/issues/1328' target='_blank'>CEED/libCEED#1328</a>.

<small>We're going to need new restrictions and new `CeedVector` lengths (assuming we keep using `CeedVector` to hold particle data, which seems appropriate since eventually they'll be able to live on GPU). I think we can just recreate that stuff once per time step. Within a time step, I think the only stored quantities that change will be vectors in the FE space (SNES residual, Krylov vectors), so that fits our standard FE assumptions. The SNES residual will visit particles, but not store anything there....</small>

<a href='https://github.com/CEED/libCEED/issues/1328' target='_blank'>View Comment</a>