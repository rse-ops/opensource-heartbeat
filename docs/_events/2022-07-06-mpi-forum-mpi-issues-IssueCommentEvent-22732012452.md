---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3047763?"
user: correaa
date: 2022-07-06
repo_name: mpi-forum/mpi-issues
html_url: https://github.com/mpi-forum/mpi-issues/issues/536
repo_url: https://github.com/mpi-forum/mpi-issues
---

<a href='https://github.com/correaa' target='_blank'>correaa</a> commented on issue <a href='https://github.com/mpi-forum/mpi-issues/issues/536' target='_blank'>mpi-forum/mpi-issues#536</a>.

<small>@Wee-Free-Scot , excellent explanation. It made me understand that, differently to `shared_ptr`, the increment/decrement of the reference counting happens only to indirect means, by creating/freeing requests and not, for example, by copying somehw the `shared_ptr`. It is possible to build a semantic `shared_ptr`, but it will have two overlapping counts. One over the "value" and one over the "internal" count. The language of `shared_ptr` assumes that there is an actual object behind (as @VictorEijkhout ) says but it doesn't matter for `shared_ptr` whether it is copiable or not.  I agree with @VictorEijkhout that, if there is an actual object, it shouldn't be copyable at this stage, but I don't know if it is a fundamental limitation or a quirk in the specification. I also disabled the copy constructor and copy assignment, but I also think that it cannot be the end of the story given that communicators can be duplicated. We can continue the discussion in the Slack MPI C++ channel....</small>

<a href='https://github.com/mpi-forum/mpi-issues/issues/536' target='_blank'>View Comment</a>