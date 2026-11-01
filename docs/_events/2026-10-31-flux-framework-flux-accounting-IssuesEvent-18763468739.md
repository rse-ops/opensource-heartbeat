---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2026-10-31
repo_name: flux-framework/flux-accounting
html_url: https://github.com/flux-framework/flux-accounting/issues/1016
repo_url: https://github.com/flux-framework/flux-accounting
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-accounting/issues/1016' target='_blank'>flux-framework/flux-accounting#1016</a>.

<p>mf_priority: pending job killed with "job info missing" if it runs before flux-accounting data arrives after plugin reload</p><small>Problem: When mf_priority is reloaded without flux-accounting data, a pending job in SCHED state can get resources before the data arrives. The plugin then raises a fatal exception in job.state.run, and the job is killed:...</small><a href='https://github.com/flux-framework/flux-accounting/issues/1016' target='_blank'>View Comment</a>