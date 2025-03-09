---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2025-03-05
repo_name: coreylowman/cudarc
html_url: https://github.com/coreylowman/cudarc/issues/340
repo_url: https://github.com/coreylowman/cudarc
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/coreylowman/cudarc/issues/340' target='_blank'>coreylowman/cudarc#340</a>.

<small>I'm not sure what's being proposed here, as `memcpy_dtoh_async` is `unsafe`, and any safe `dtoh_copy_pinned` would take a `&mut PinnedHostSlice<T>`. But it's true that it's necessary to prevent passing the same slice as destination for multiple copies (or as immutable arguments) on different streams....</small>

<a href='https://github.com/coreylowman/cudarc/issues/340' target='_blank'>View Comment</a>