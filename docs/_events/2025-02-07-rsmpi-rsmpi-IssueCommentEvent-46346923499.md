---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2025-02-07
repo_name: rsmpi/rsmpi
html_url: https://github.com/rsmpi/rsmpi/issues/197
repo_url: https://github.com/rsmpi/rsmpi
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/rsmpi/rsmpi/issues/197' target='_blank'>rsmpi/rsmpi#197</a>.

<small>@oxcrow Try building with `RUSTFLAGS='-C panic=abort' (or [put it](https://doc.rust-lang.org/cargo/reference/profiles.html#) in your profile). If that works like the C program, then this is the issue. Panics generally interact poorly with collective semantics so it's best to minimize when that can happen....</small>

<a href='https://github.com/rsmpi/rsmpi/issues/197' target='_blank'>View Comment</a>