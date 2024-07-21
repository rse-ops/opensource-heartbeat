---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2024-07-18
repo_name: EnzymeAD/rust
html_url: https://github.com/EnzymeAD/rust/issues/137
repo_url: https://github.com/EnzymeAD/rust
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/EnzymeAD/rust/issues/137' target='_blank'>EnzymeAD/rust#137</a>.

<small>The symbols like `RSMPI_DOUBLE` exist because `MPI_DOUBLE` is a macro so we can't otherwise use it from Rust. With a user-defined operation, it would not map to a static value. I suppose Enzyme may not support user-defined `MPI_Op`s, but if that's desired in the roadmap, it would be necessary to intercept/augment `MPI_Op_create` and keep a run-time table to the derivative of the user's operation. When I pass the op in as `Const` to the differentiated function, I'm still getting the error pointing back to `RSMPI_DOUBLE`, which I don't really understand except for inlining....</small>

<a href='https://github.com/EnzymeAD/rust/issues/137' target='_blank'>View Comment</a>