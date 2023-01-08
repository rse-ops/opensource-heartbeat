---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-01-06
repo_name: rsmpi/rsmpi
html_url: https://github.com/rsmpi/rsmpi/issues/144
repo_url: https://github.com/rsmpi/rsmpi
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/rsmpi/rsmpi/issues/144' target='_blank'>rsmpi/rsmpi#144</a>.

<small>Can you look at `immediate_multiple_requests.rs` to see if it answers your question about scope? The issue is that your messages exceed the MPI implementation's "eager threshold" (usually an environment-tunable parameter, but your code shouldn't rely on it) and thus sends can't complete until receives are posted, but as you've written it, you can't get around to posting receives until your rank has waited on its sends....</small>

<a href='https://github.com/rsmpi/rsmpi/issues/144' target='_blank'>View Comment</a>