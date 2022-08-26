---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-08-26
repo_name: rsmpi/rsmpi
html_url: https://github.com/rsmpi/rsmpi/pull/128
repo_url: https://github.com/rsmpi/rsmpi
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/rsmpi/rsmpi/pull/128' target='_blank'>rsmpi/rsmpi#128</a>.

<small>I'd think we want to ensure that the user *cannot* send from `MaybeUninit<T>`. Once received, the written buffer would be initialized. I could imagine an interface in which receives return a suitably typed slice from the provided buffer, but that might have undesirable side-effects....</small>

<a href='https://github.com/rsmpi/rsmpi/pull/128' target='_blank'>View Comment</a>