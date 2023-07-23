---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/62483075?"
user: eliasboegel
date: 2023-07-22
repo_name: rayon-rs/rayon
html_url: https://github.com/rayon-rs/rayon/issues/798
repo_url: https://github.com/rayon-rs/rayon
---

<a href='https://github.com/eliasboegel' target='_blank'>eliasboegel</a> commented on issue <a href='https://github.com/rayon-rs/rayon/issues/798' target='_blank'>rayon-rs/rayon#798</a>.

<small>I must agree with @rcarson3 here. There has been a monumental amount of funded work going into this topic in the form of several approaches. I think the best starting point there would be to have a look at [Kokkos](https://github.com/kokkos/kokkos), particularly as they essentially have achieved mapping of a single-source kernel to both CPUs and GPUs with a library-only approach. A compiler-based approach (e.g. SYLC) is another option, which for Rust is somewhat easier to deal with than for C++, as in Rust only one single compiler is widely used instead of several different vendor compilers. Kokkos (and the other libraries @rcarson3 mentioned) enjoy the benefits of having had a lot of engineering work go into them, with a lot of lessons learned along the way from many different architectures. Moreover, there is some cooperation between hardware vendors and the developers of the large parallel programming models. I don't see any reason to start any design work from scratch instead of aligning with the existing and mature work in this topic....</small>

<a href='https://github.com/rayon-rs/rayon/issues/798' target='_blank'>View Comment</a>