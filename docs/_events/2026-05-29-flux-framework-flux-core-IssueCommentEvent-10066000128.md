---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2026-05-29
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/7644
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/7644' target='_blank'>flux-framework/flux-core#7644</a>.

<small>@kkier suggested setting `allow_abbrev=False` for argparse which would help in this specific case. However, the behavior we want from argparse is the POSIX behavior where option processing stops at the first non-option argument (See `POSIXLY_CORRECT` in [getopt_long(3)](https://linux.die.net/man/3/getopt_long)). I haven't looked in awhile, but last I checked the argparse maintainers were unwilling to implement that behavior....</small>

<a href='https://github.com/flux-framework/flux-core/issues/7644' target='_blank'>View Comment</a>