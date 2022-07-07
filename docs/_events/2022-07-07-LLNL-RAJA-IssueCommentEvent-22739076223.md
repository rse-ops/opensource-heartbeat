---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-07-07
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/pull/1284
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/LLNL/RAJA/pull/1284' target='_blank'>LLNL/RAJA#1284</a>.

<small>As far as I can tell with the tests I have on hand, this should export all the targets we need for both in-tree and out-of-tree camp builds.  The only visible difference should be that the `RAJA::<backend>` targets may or may not be named that, and there's no separate `raja-blt-targets.cmake` file because the necessary targets are part of the RAJATargets.cmake file. Both of those are meant to be an implementation detail, so I'm not sure how much we care about that, it's possible someone relies on those details....</small>

<a href='https://github.com/LLNL/RAJA/pull/1284' target='_blank'>View Comment</a>