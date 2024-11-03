---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/169947?"
user: garlick
date: 2024-11-01
repo_name: flux-framework/flux-security
html_url: https://github.com/flux-framework/flux-security/pull/186
repo_url: https://github.com/flux-framework/flux-security
---

<a href='https://github.com/garlick' target='_blank'>garlick</a> commented on issue <a href='https://github.com/flux-framework/flux-security/pull/186' target='_blank'>flux-framework/flux-security#186</a>.

<small>I grabbed your snapshot from last night and put it on my test cluster.  This morning I made some minimal changes to job-exec on my `issue#6406` branch to send SIGUSR1 instead of imp-kill when shell termination methods fail.  Then I ran a test on my system by starting a long running job, sending the flux-shell a SIGSTOP, then canceling the job.  Looks good!  Flux on rank 0 logged:...</small>

<a href='https://github.com/flux-framework/flux-security/pull/186' target='_blank'>View Comment</a>