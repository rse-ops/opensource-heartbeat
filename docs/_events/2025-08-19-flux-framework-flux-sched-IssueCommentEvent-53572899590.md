---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-08-19
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/986
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/flux-framework/flux-sched/issues/986' target='_blank'>flux-framework/flux-sched#986</a>.

<small>Actually, I think it comes down to this:  We have the index into the list of RSMI devices that we want to pull, it looks like we have to iterate over them to find that (can probably also use a filter to get there, or use cousin walking or something smarter that I can't think of right now). Once we have it, we can use the suffix of the name (which is utterly insane but it seems there isn't a field for it for some crazy reason) or we can use the `AMDUUID=a30d0d26ba377c92` field from the osdev attributes and put that directly into the ROCM_VISIBLE_DEVICES.  That value is a lot less pretty, but it's _stable_ so no matter how many times that variable gets applied into child processes and restricted environments it stays correct.  Where `ROCM_VISIBLE_DEVICES=3` becomes an error if it's applied twice....</small>

<a href='https://github.com/flux-framework/flux-sched/issues/986' target='_blank'>View Comment</a>