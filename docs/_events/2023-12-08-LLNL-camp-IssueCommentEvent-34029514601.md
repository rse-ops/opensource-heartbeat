---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2023-12-08
repo_name: LLNL/camp
html_url: https://github.com/LLNL/camp/issues/144
repo_url: https://github.com/LLNL/camp
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/LLNL/camp/issues/144' target='_blank'>LLNL/camp#144</a>.

<small>The main trick really is dealing with the lifetime and single cleanup issue.  Using variant would remove the atomic on each copy, so that would be nice and might be worth a try.  The semantics would be a bit different, but we don't do anything on destruction so it should work out.  Might even be fine to use std::any now that I think about it, bit different tradeoff, worth trying I think....</small>

<a href='https://github.com/LLNL/camp/issues/144' target='_blank'>View Comment</a>