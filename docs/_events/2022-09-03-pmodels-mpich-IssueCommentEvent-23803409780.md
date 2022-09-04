---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-09-03
repo_name: pmodels/mpich
html_url: https://github.com/pmodels/mpich/issues/3591
repo_url: https://github.com/pmodels/mpich
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/pmodels/mpich/issues/3591' target='_blank'>pmodels/mpich#3591</a>.

<small>Thanks for your reply. This is very informative, though Endpoints is really what we were excited about. The issue is that we'd like to use the MPI programming model across threads within a library. But the library has callbacks to user code and implementing those callbacks in a different process (as with internal `MPI_Comm_spawn`) requires the calling application to "think MPI" and design their data structures appropriately. Meanwhile, using fork-join thread parallelism is catastrophic to performance because it's similar cost to off-node communication even for embarrassingly parallel operations. Anyway, it's kind of sad to hear Endpoints has been dropped with seemingly nothing on the horizon for this use case....</small>

<a href='https://github.com/pmodels/mpich/issues/3591' target='_blank'>View Comment</a>