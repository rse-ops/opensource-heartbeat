---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2026-04-25
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/7550
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/7550' target='_blank'>flux-framework/flux-core#7550</a>.

<small>This could be solved by the mapper introduced in #7566, since it is able to set or adjust arbitrary systemd properties per job, and has access to the locally assigned resources. As a first cut, the default `HwlocMapper` could scale `MemoryMax` by the ratio of cores allocated to the job vs available cores, e.g. if `MemoryMax=98%` in the config, and a job is assigned half the cores, the mapper could return `MemoryMax=49%`. ...</small>

<a href='https://github.com/flux-framework/flux-core/issues/7550' target='_blank'>View Comment</a>