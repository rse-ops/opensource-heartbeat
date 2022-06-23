---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/2652545?"
user: milroy
date: 2022-06-16
repo_name: milroy/flux-sched
html_url: https://github.com/milroy/flux-sched/commit/1e6aec07a57a75551ef18e3b2bb6fcadc3acc257
repo_url: https://github.com/milroy/flux-sched
---

<a href='https://github.com/milroy' target='_blank'>milroy</a> pushed to <a href='https://github.com/milroy/flux-sched' target='_blank'>milroy/flux-sched</a>

<small>jobspec: add properties support

Problem: RFC14 and RFC25 now supports property-based constraints (via
the "attributes.system.constraints.properties" key) but libjobspec does
not recognize this key.

Add fields to deserialize constraints.properties into.

Throw an exception if a property string contains an invalid character
(! & ' " ^ ` | ( )) or if the value of properties is not a sequence
except when '^' appears as the first character of the property.</small>

<a href='https://github.com/milroy/flux-sched/commit/1e6aec07a57a75551ef18e3b2bb6fcadc3acc257' target='_blank'>View Commit</a>