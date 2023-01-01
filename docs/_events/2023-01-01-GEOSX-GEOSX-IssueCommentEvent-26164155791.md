---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5116892?"
user: rrsettgast
date: 2023-01-01
repo_name: GEOSX/GEOSX
html_url: https://github.com/GEOSX/GEOSX/pull/2230
repo_url: https://github.com/GEOSX/GEOSX
---

<a href='https://github.com/rrsettgast' target='_blank'>rrsettgast</a> commented on issue <a href='https://github.com/GEOSX/GEOSX/pull/2230' target='_blank'>GEOSX/GEOSX#2230</a>.

<small>@kjdugan I suspect that this fix may not actually provide a rock solid "fix". In the discussion #2173 I propose that a rewrite of the wait functionalities ignores  all `MPI_Status` and `MPI_Request` associated with the send operations. I might be incorrect, but if I am correct then this is a fundamentally unsafe set of operations that needs to be addressed directly. While the `MPI_Barrier` may "fix" the problem, perhaps it does not fix the problem directly. ...</small>

<a href='https://github.com/GEOSX/GEOSX/pull/2230' target='_blank'>View Comment</a>