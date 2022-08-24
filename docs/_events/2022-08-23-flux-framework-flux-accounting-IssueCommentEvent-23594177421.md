---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/20131404?"
user: cmoussa1
date: 2022-08-23
repo_name: flux-framework/flux-accounting
html_url: https://github.com/flux-framework/flux-accounting/pull/264
repo_url: https://github.com/flux-framework/flux-accounting
---

<a href='https://github.com/cmoussa1' target='_blank'>cmoussa1</a> commented on issue <a href='https://github.com/flux-framework/flux-accounting/pull/264' target='_blank'>flux-framework/flux-accounting#264</a>.

<small>OK, I've squashed and force-pushed a change to hopefully and correctly use `json_decref ()` in the functions that create the JSON objects. Like you mentioned in your suggestions above, I created a `goto error` idiom that `decref`s the `json_t` objects that are created in the two helper functions in the case when an error occurs. Let me know if this is better and/or I need to make additional changes. Thanks for helping me work through this! :P ...</small>

<a href='https://github.com/flux-framework/flux-accounting/pull/264' target='_blank'>View Comment</a>