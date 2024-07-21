---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2024-07-18
repo_name: flux-framework/flux-sched
html_url: https://github.com/flux-framework/flux-sched/issues/1251
repo_url: https://github.com/flux-framework/flux-sched
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> open issue <a href='https://github.com/flux-framework/flux-sched/issues/1251' target='_blank'>flux-framework/flux-sched#1251</a>.

<p>housekeeping only drains nodes if systemd unit can be run</p><small>The housekeeping service relies on the systemd unit to drain ranks that fail housekeeping. However, if the housekeeping systemd service isn't configured or fails to start, then the node is not drained. Instead the node is put back into service without housekeeping being run, which could cause any number of failures....</small><a href='https://github.com/flux-framework/flux-sched/issues/1251' target='_blank'>View Comment</a>