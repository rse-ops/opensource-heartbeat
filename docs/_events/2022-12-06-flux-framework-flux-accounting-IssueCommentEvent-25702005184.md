---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20131404?"
user: cmoussa1
date: 2022-12-06
repo_name: flux-framework/flux-accounting
html_url: https://github.com/flux-framework/flux-accounting/pull/294
repo_url: https://github.com/flux-framework/flux-accounting
---

<a href='https://github.com/cmoussa1' target='_blank'>cmoussa1</a> commented on issue <a href='https://github.com/flux-framework/flux-accounting/pull/294' target='_blank'>flux-framework/flux-accounting#294</a>.

<small>So that was odd! My `python-lint` check was failing with an error message saying it could not locate Python `3.6`. From some quick and rough Google searches it looks like it _might_ have something to do with the latest version of Ubuntu being used (I was using `ubuntu-latest`): https://github.com/actions/setup-python/issues/162. I updated the version number to match flux-core's Ubuntu version for the `python-lint` check, and now it works as excepted, so I think I'll move the most recent commit on this PR to another branch and post a separate, small fix PR. ...</small>

<a href='https://github.com/flux-framework/flux-accounting/pull/294' target='_blank'>View Comment</a>