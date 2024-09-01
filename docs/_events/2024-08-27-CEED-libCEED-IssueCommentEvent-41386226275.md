---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2024-08-27
repo_name: CEED/libCEED
html_url: https://github.com/CEED/libCEED/issues/1650
repo_url: https://github.com/CEED/libCEED
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/CEED/libCEED/issues/1650' target='_blank'>CEED/libCEED#1650</a>.

<small>Hi, thanks for the question. We haven't added `cuda`/`hip`/`sycl` features to the `libceed-sys` package, but you can build `libceed.so` any way you like and then use the `system` feature to use that pre-built library instead of having `libceed-sys/build.rs` build its own. We'd be happy to accept a pull request that added such features, though they may be somewhat brittle because one needs `build.rs` to find the toolchain (CUDA) that the user intends....</small>

<a href='https://github.com/CEED/libCEED/issues/1650' target='_blank'>View Comment</a>