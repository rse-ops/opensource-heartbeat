---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2025-01-17
repo_name: rust-lang/rust
html_url: https://github.com/rust-lang/rust/issues/135516
repo_url: https://github.com/rust-lang/rust
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/rust-lang/rust/issues/135516' target='_blank'>rust-lang/rust#135516</a>.

<small>It's nigh impossible to use shared memory (or write any useful kernel) without the concept of thread indices, which are in `core::arch::nvptx`. I had in mind that there would be vendor-specific intrinsics using that vendor's preferred terminology (thus my initial suggestion that the feature gate would be `stdarch_nvptx`, same as #111199) and we could later define a common subset using a single consistent nomenclature. I think it would be confusing if users of vendor-specific features had to deal with two nomenclatures, so I'd be in favor of the the "re-expose" strategy....</small>

<a href='https://github.com/rust-lang/rust/issues/135516' target='_blank'>View Comment</a>