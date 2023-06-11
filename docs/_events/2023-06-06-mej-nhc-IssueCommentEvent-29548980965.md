---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/2934441?"
user: mej
date: 2023-06-06
repo_name: mej/nhc
html_url: https://github.com/mej/nhc/pull/47
repo_url: https://github.com/mej/nhc
---

<a href='https://github.com/mej' target='_blank'>mej</a> commented on issue <a href='https://github.com/mej/nhc/pull/47' target='_blank'>mej/nhc#47</a>.

<small>Fixed via #121 instead; closing.  NHC goes to great lengths to avoid spawning subshells or other processes wherever and whenever possible.  The culprit turned out to be the way the kernel and Bash handle `/proc` filesystem reads, so in lieu of `grep`, a more efficient, one-shot read-and-store method was chosen instead....</small>

<a href='https://github.com/mej/nhc/pull/47' target='_blank'>View Comment</a>