---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-08-16
repo_name: jeremiah-corrado/fem_2d
html_url: https://github.com/jeremiah-corrado/fem_2d/issues/2
repo_url: https://github.com/jeremiah-corrado/fem_2d
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/jeremiah-corrado/fem_2d/issues/2' target='_blank'>jeremiah-corrado/fem_2d#2</a>.

<small>I see your intent with quadrature and why a naive $f(x,y)$ interface isn't good for tabulated basis functions. However, a common technique is to provide additional inputs, such as $f(x,y,u,v)$, where $u,v$ have been tabulated at quadrature points. That said, optimized implementations (such as in libCEED) will handle the test functions via matrix operations rather than in an integral interface that returns a scalar. (It's quite surprising the extent to which finite element books, libraries, and commercial codes use inefficient abstractions and data structures.) Anyway, this is kind of a rabbit hole, but it's something you may want to revisit if/when finite element algebra becomes a bottleneck....</small>

<a href='https://github.com/jeremiah-corrado/fem_2d/issues/2' target='_blank'>View Comment</a>