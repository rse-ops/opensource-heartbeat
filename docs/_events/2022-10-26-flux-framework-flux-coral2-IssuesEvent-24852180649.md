---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2022-10-26
repo_name: flux-framework/flux-coral2
html_url: https://github.com/flux-framework/flux-coral2/issues/35
repo_url: https://github.com/flux-framework/flux-coral2
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> open issue <a href='https://github.com/flux-framework/flux-coral2/issues/35' target='_blank'>flux-framework/flux-coral2#35</a>.

<p>cray_pals plugin should accept task distribution from flux shell</p><small>Problem: flux-core needs to support "cyclic" task distribution as mentioned in flux-framework/flux-core#4706.  I just opened flux-framework/flux-core#4725  against the flux-core pmi shell plugin to have it accept the shell's task distribution instead of just grabbing per-shell task counts and assuming a "block" task distribution.   I _think_ the cray_pals shell plugin is patterned after flux-core's pmi plugin.  At least I do see it fetching the `ntasks` key using `flux_shell_rank_info_unpack()` to get the task count per shell, rather than the `taskids` key which contains the actual task ranks....</small><a href='https://github.com/flux-framework/flux-coral2/issues/35' target='_blank'>View Comment</a>