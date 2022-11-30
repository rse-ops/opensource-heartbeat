---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-11-29
repo_name: linalg-rs/sandbox
html_url: https://github.com/linalg-rs/sandbox/issues/7
repo_url: https://github.com/linalg-rs/sandbox
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/linalg-rs/sandbox/issues/7' target='_blank'>linalg-rs/sandbox#7</a>.

<small>Yeah, MPI is a clumsy dependency, especially in Rust land. It's typical for a distributed sparse matrix to have two sequential matrices, one for the diagonal block and one for the off-diagonal block. For PDE-type applications, most everyone uses 1D decompositions (usually row partitioning), but for irregular operations (like social network graphs or bundle adjustment), there are benefits to supporting 2D decompositions (like `CombBLAS` uses, often in a randomized ordering, which gives up data locality in exchange for load balancing)....</small>

<a href='https://github.com/linalg-rs/sandbox/issues/7' target='_blank'>View Comment</a>