---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/20131404?"
user: cmoussa1
date: 2025-09-24
repo_name: flux-framework/flux-accounting
html_url: https://github.com/flux-framework/flux-accounting/issues/754
repo_url: https://github.com/flux-framework/flux-accounting
---

<a href='https://github.com/cmoussa1' target='_blank'>cmoussa1</a> open issue <a href='https://github.com/flux-framework/flux-accounting/issues/754' target='_blank'>flux-framework/flux-accounting#754</a>.

<p>plugin: held jobs still kept in `Association` object even if held jobs are cancelled</p><small>I just ran a quick test in my Docker environment and I noticed that if a job is held due to a flux-accounting dependency and the held job is cancelled, its ID and dependency are still tracked in the `Association` object in the plugin. So, when a currently-running job is finished running, the plugin will still attempt to remove any dependencies from that held job, which is incorrect:...</small><a href='https://github.com/flux-framework/flux-accounting/issues/754' target='_blank'>View Comment</a>