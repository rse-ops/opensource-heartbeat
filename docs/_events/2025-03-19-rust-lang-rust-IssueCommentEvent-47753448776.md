---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2025-03-19
repo_name: rust-lang/rust
html_url: https://github.com/rust-lang/rust/issues/135516
repo_url: https://github.com/rust-lang/rust
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/rust-lang/rust/issues/135516' target='_blank'>rust-lang/rust#135516</a>.

<small>So `Cell` and `UnsafeCell` are not `Sync`. (Unscoped `Sync` isn't correct for what we need either, since shared memory can only be shared among a thread block, and we don't currently have a scoped `Sync` to express that.) However, the implementation of `Cell` really is unsound if shared between threads. Is it better for the user to work with `MaybeUninit<[UnsafeCell<T>; N]>` than `(*mut T, usize)`?...</small>

<a href='https://github.com/rust-lang/rust/issues/135516' target='_blank'>View Comment</a>