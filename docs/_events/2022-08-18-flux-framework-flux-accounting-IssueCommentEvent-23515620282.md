---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20131404?"
user: cmoussa1
date: 2022-08-18
repo_name: flux-framework/flux-accounting
html_url: https://github.com/flux-framework/flux-accounting/issues/262
repo_url: https://github.com/flux-framework/flux-accounting
---

<a href='https://github.com/cmoussa1' target='_blank'>cmoussa1</a> commented on issue <a href='https://github.com/flux-framework/flux-accounting/issues/262' target='_blank'>flux-framework/flux-accounting#262</a>.

<small>Just to follow up on this, @garlick brought up a great point in our weekly meeting today that perhaps the cause of this issue was some due to some mishandling of some active jobs in the PENDING state after a broker restart due to a seg fault on Fluke. When the system instance started up again, perhaps the priority plugin miscounted the already active jobs and incorrectly added dependencies on subsequently submitted jobs....</small>

<a href='https://github.com/flux-framework/flux-accounting/issues/262' target='_blank'>View Comment</a>