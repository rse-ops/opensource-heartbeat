---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20131404?"
user: cmoussa1
date: 2026-02-19
repo_name: flux-framework/flux-accounting
html_url: https://github.com/flux-framework/flux-accounting/pull/818
repo_url: https://github.com/flux-framework/flux-accounting
---

<a href='https://github.com/cmoussa1' target='_blank'>cmoussa1</a> commented on issue <a href='https://github.com/flux-framework/flux-accounting/pull/818' target='_blank'>flux-framework/flux-accounting#818</a>.

<small>I'm still seeing some unexpected and random errors from the `coverage` builder during the `create_db()` call. I wonder if it has anything to do with the syntax of creating the DB itself. The [`sqlite3`](https://docs.python.org/3/library/sqlite3.html#sqlite3.connect) documentation examples use `=` instead of `:` in their `.connect()` call, and I wonder if this syntax error might be causing the creation of the database to not be opened with a read-write connection. Maybe this is only being caught by CI every now and then. I'm going to add another commit to change this `.connect()` call and see if that resolves it....</small>

<a href='https://github.com/flux-framework/flux-accounting/pull/818' target='_blank'>View Comment</a>