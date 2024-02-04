---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20131404?"
user: cmoussa1
date: 2024-02-01
repo_name: flux-framework/flux-accounting
html_url: https://github.com/flux-framework/flux-accounting/issues/414
repo_url: https://github.com/flux-framework/flux-accounting
---

<a href='https://github.com/cmoussa1' target='_blank'>cmoussa1</a> commented on issue <a href='https://github.com/flux-framework/flux-accounting/issues/414' target='_blank'>flux-framework/flux-accounting#414</a>.

<small>I just tried running some basic `view-job-records` commands and I was unable to get it working as well. The error above looks like something is wrong with the command being parsed; if no path to the job-archive DB is set (it is typically located in `/var/lib/flux/`), flux-accounting fails to assume a default path (indicating the `NoneType` error for `path`). But even passing this path to the command doesn't seem to be working either, for I get a `Expecting value: line 1 column 1 (char 0)`. Perhaps there is an issue with parsing the arguments in the `flux-accounting` command service. I can look into this....</small>

<a href='https://github.com/flux-framework/flux-accounting/issues/414' target='_blank'>View Comment</a>