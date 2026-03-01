---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2026-02-26
repo_name: flux-framework/flux-coral2
html_url: https://github.com/flux-framework/flux-coral2/issues/452
repo_url: https://github.com/flux-framework/flux-coral2
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-coral2/issues/452' target='_blank'>flux-framework/flux-coral2#452</a>.

<small>One other point is that the scheme above won't apply for a subinstance launched with some brokers on rabbits. The rabbit property will be preserved, but the default queue in the instance will happily run stuff on the rabbits by default. Users will have to be aware that they need to run normal jobs using `--requires=-rabbit`, or we can look into ways automatically set up queues, exclude rabbits by default, or whatever makes the most sense for the probable use cases....</small>

<a href='https://github.com/flux-framework/flux-coral2/issues/452' target='_blank'>View Comment</a>