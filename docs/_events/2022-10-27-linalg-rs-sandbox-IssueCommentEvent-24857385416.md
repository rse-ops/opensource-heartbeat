---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-10-27
repo_name: linalg-rs/sandbox
html_url: https://github.com/linalg-rs/sandbox/issues/2
repo_url: https://github.com/linalg-rs/sandbox
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/linalg-rs/sandbox/issues/2' target='_blank'>linalg-rs/sandbox#2</a>.

<small>Yeah, I don't know how to balance this. For high performance work at larger sizes, we'll generally need access to tiles (even with specified alignment and strides) so iterators won't be over scalar entries and packing would have to be done even if the types aren't converted. It's messier for small sizes and sparse things because conversion has overhead and it's hard to vectorize. With an SpMV $y \gets A x$ where $A$ is f32 and $x$ is f64, it's likely better to convert $x$ up-front unless there are very few nonzeros per row....</small>

<a href='https://github.com/linalg-rs/sandbox/issues/2' target='_blank'>View Comment</a>