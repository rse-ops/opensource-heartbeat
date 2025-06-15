---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/49216024?"
user: bgunnar5
date: 2025-06-12
repo_name: LLNL/merlin
html_url: https://github.com/LLNL/merlin/pull/512
repo_url: https://github.com/LLNL/merlin
---

<a href='https://github.com/bgunnar5' target='_blank'>bgunnar5</a> commented on issue <a href='https://github.com/LLNL/merlin/pull/512' target='_blank'>LLNL/merlin#512</a>.

<small>@lucpeterson after spending hours trying to research and implement this, turns out Redis _only_ accepts plaintext in the redis.conf file. Therefore, even if we encrypt the password with Fernet, Redis will just use the encrypted string as the password. I don't think there's any way around this so those last three CodeQL issues are unable to be resolved....</small>

<a href='https://github.com/LLNL/merlin/pull/512' target='_blank'>View Comment</a>