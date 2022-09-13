---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-09-13
repo_name: rsmpi/rsmpi
html_url: https://github.com/rsmpi/rsmpi/issues/133
repo_url: https://github.com/rsmpi/rsmpi
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/rsmpi/rsmpi/issues/133' target='_blank'>rsmpi/rsmpi#133</a>.

<small>I don't know if point-to-point can even be meaningfully "safe" without significant performance consequences. But point-to-point is usually a building block for higher level collectives. And I could imagine making typed bands containing a communicator and a statically-specified type. Creating such a band would be formally collective, but only for error-checking that the types are consistent. Anyway, I'm mostly interested in making collectives safe and making it possible to write domain-relevant collectives in Rust (with or without a limited amount of unsafe)....</small>

<a href='https://github.com/rsmpi/rsmpi/issues/133' target='_blank'>View Comment</a>