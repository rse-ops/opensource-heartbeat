---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/20131404?"
user: cmoussa1
date: 2026-10-16
repo_name: flux-framework/flux-accounting
html_url: https://github.com/flux-framework/flux-accounting/issues/1005
repo_url: https://github.com/flux-framework/flux-accounting
---

<a href='https://github.com/cmoussa1' target='_blank'>cmoussa1</a> open issue <a href='https://github.com/flux-framework/flux-accounting/issues/1005' target='_blank'>flux-framework/flux-accounting#1005</a>.

<p>plugin: factor weights get overwritten on plugin load</p><small>While working on #995, I discovered a bug in the priority plugin where the factor weights were getting overwritten when loading a plugin with configured factor weights. This is because `initialize_plugin ()` is called *before* the factors are initialized:...</small><a href='https://github.com/flux-framework/flux-accounting/issues/1005' target='_blank'>View Comment</a>