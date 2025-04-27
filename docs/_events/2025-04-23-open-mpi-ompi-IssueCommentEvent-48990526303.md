---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/7818666?"
user: hppritcha
date: 2025-04-23
repo_name: open-mpi/ompi
html_url: https://github.com/open-mpi/ompi/pull/13206
repo_url: https://github.com/open-mpi/ompi
---

<a href='https://github.com/hppritcha' target='_blank'>hppritcha</a> commented on issue <a href='https://github.com/open-mpi/ompi/pull/13206' target='_blank'>open-mpi/ompi#13206</a>.

<small>I did some investigations here and it looks like some changes in this PR somehow broke the connection management in the TCP BTL.  If one runs main with mpi4py with OMPI_MCA_btl=self,tcp things work.  But with this PR it doesn't.  There are some suspicioius differences between the opal_config.h generated in this PR vs main and I suspect that's a symptom of other config differences that wind up giving the TCP BTL problems....</small>

<a href='https://github.com/open-mpi/ompi/pull/13206' target='_blank'>View Comment</a>