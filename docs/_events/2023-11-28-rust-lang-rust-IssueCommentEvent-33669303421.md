---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-11-28
repo_name: rust-lang/rust
html_url: https://github.com/rust-lang/rust/issues/88345
repo_url: https://github.com/rust-lang/rust
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/rust-lang/rust/issues/88345' target='_blank'>rust-lang/rust#88345</a>.

<small>I just want to make sure folks in this thread are aware of the Rust for Morello/CHERI [Pre-RFC `usize` semantics](https://internals.rust-lang.org/t/pre-rfc-usize-semantics/19444/22), which would imply `size_t` = `usize` and `ptrdiff_t` = `isize`. This would be consistent with [`strict_provenance`](https://github.com/rust-lang/rust/issues/95228). These want to move away from conflating `intptr_t`/`uintptr_t` with `isize`/`usize`, and it seems the main dilemma is between compatibility (keep working without warnings on non-CHERI) versus strictness (warnings or errors for bad conversions even on non-CHERI architectures where they are harmless)....</small>

<a href='https://github.com/rust-lang/rust/issues/88345' target='_blank'>View Comment</a>