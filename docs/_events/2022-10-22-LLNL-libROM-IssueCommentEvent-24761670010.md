---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2022-10-22
repo_name: LLNL/libROM
html_url: https://github.com/LLNL/libROM/pull/150
repo_url: https://github.com/LLNL/libROM
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/LLNL/libROM/pull/150' target='_blank'>LLNL/libROM#150</a>.

<small>@jtlau Thanks for watching this PR. I was planning to ask whether this PR might break something, as it makes it impossible to call `endSamples` twice, or to call both `endSamples` and `writeSnapshot`. This is why it is a WIP. It is helpful to know that you do not see a practical use for calling both, except in a unit test. I will test Laghos and our other examples with this PR to see if anything is broken, and of course anyone who sees an issue with this PR should comment. I can also add an error message if `endSamples` or `writeSnapshot` is called after the writer is deleted, since an error message would be more helpful than the current version that simply fails....</small>

<a href='https://github.com/LLNL/libROM/pull/150' target='_blank'>View Comment</a>