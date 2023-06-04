---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/874707?"
user: SteVwonder
date: 2023-06-03
repo_name: flux-framework/flux-depend
html_url: https://github.com/flux-framework/flux-depend/pull/4
repo_url: https://github.com/flux-framework/flux-depend
---

<a href='https://github.com/SteVwonder' target='_blank'>SteVwonder</a> commented on issue <a href='https://github.com/flux-framework/flux-depend/pull/4' target='_blank'>flux-framework/flux-depend#4</a>.

<small>Hey @vsoch! I used this repo for similar reasons (an excuse to use rust in my day job). The high level idea was to implement a module for flux that could provide the "OpenMP-style" dependencies defined in this RFC: https://flux-framework.readthedocs.io/projects/flux-rfc/en/latest/spec_26.html. The summary motivation for those type of dependencies is they let you specify a DAG of dependencies without (as a user) having to deal with the job ids - so your higher-level workflow system logic is simpler and your dependency specification is identical across workflow runs. And then from a system/Flux-perspective, they are nice because they enable to be more stateless. You don't have to keep a history of all jobs from all time nor due any DB lookups (e.g., a `afterok:<JOBID>` requires looking up the completion status of `<JOBID>` which may have finished days ago)....</small>

<a href='https://github.com/flux-framework/flux-depend/pull/4' target='_blank'>View Comment</a>