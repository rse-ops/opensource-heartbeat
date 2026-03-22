---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2026-03-21
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/939
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-sched/issues/939' target='_blank'>flux-framework/flux-sched#939</a>.

<p>resources are not scheduled fairly among competing queues of job requests</p><small>Problem: when multiple queues are defined, fluxion schedules all jobs in the first queue before looking at the next queue.  The queues are thus implicitly prioritized according to the order defined, with no available mechanisms to prevent starvation or ensure progress for all queues....</small><a href='https://github.com/flux-framework/flux-sched/issues/939' target='_blank'>View Comment</a>