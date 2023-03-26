---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2023-03-23
repo_name: LLNL/libROM
html_url: https://github.com/LLNL/libROM/issues/195
repo_url: https://github.com/LLNL/libROM
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/LLNL/libROM/issues/195' target='_blank'>LLNL/libROM#195</a>.

<small>1. There are some parameters that can be experimented with in `Options`, along with `isNextSample` to determine when `takeSample` should be called. This basically checks for how much the snapshot variable is changing over time, to give an indicator of when a new sample should be taken with `takeSample`. I am not aware of any examples where this works well. In my experience, it is best just to subsample manually, by calling `takeSample` every 1 out of N times, where N is a parameter that you set in your simulation....</small>

<a href='https://github.com/LLNL/libROM/issues/195' target='_blank'>View Comment</a>