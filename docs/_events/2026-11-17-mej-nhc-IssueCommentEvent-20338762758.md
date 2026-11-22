---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2934441?"
user: mej
date: 2026-11-17
repo_name: mej/nhc
html_url: https://github.com/mej/nhc/issues/77
repo_url: https://github.com/mej/nhc
---

<a href='https://github.com/mej' target='_blank'>mej</a> commented on issue <a href='https://github.com/mej/nhc/issues/77' target='_blank'>mej/nhc#77</a>.

<small>The kernel only "knows" the file handle is stale once you try to access it; in other words, it's active, not passive.  `check_fs_mount()` is intentionally passive for the reasons stated above (and in the docs), but other checks aren't (e.g., `check_fs_free()` and friends, which *do* use `df`)....</small>

<a href='https://github.com/mej/nhc/issues/77' target='_blank'>View Comment</a>