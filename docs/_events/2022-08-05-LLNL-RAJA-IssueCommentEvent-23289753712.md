---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-08-05
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/issues/1307
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/LLNL/RAJA/issues/1307' target='_blank'>LLNL/RAJA#1307</a>.

<small>Good point about simd_exec, I'm honestly not sure about that one.  As it is it may or may not do a whole lot, but if we treat it as unsequenced or a safe_len of 1 then it would probably have pretty consistent effect.  Maybe worth testing to see if we want to keep it and if so in what form, especially since @ajkunen's explicit simd stuff has landed....</small>

<a href='https://github.com/LLNL/RAJA/issues/1307' target='_blank'>View Comment</a>