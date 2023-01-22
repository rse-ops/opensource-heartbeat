---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/14316120?"
user: bwpriest
date: 2023-01-12
repo_name: LLNL/saltatlas
html_url: https://github.com/LLNL/saltatlas/issues/27
repo_url: https://github.com/LLNL/saltatlas
---

<a href='https://github.com/bwpriest' target='_blank'>bwpriest</a> commented on issue <a href='https://github.com/LLNL/saltatlas/issues/27' target='_blank'>LLNL/saltatlas#27</a>.

<small>It looks like the number of partitions and number of hops plays a role, which makes sense. If there are too many partitions and `saltatlas` cannot find `k` neighbors within `hops` neighboring partitions it seems to return whatever it does find. This is probably an edge case, but I feel that we should throw a warning or something when this happens....</small>

<a href='https://github.com/LLNL/saltatlas/issues/27' target='_blank'>View Comment</a>