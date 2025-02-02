---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/7818666?"
user: hppritcha
date: 2025-02-01
repo_name: open-mpi/ompi
html_url: https://github.com/open-mpi/ompi/pull/13073
repo_url: https://github.com/open-mpi/ompi
---

<a href='https://github.com/hppritcha' target='_blank'>hppritcha</a> commented on issue <a href='https://github.com/open-mpi/ompi/pull/13073' target='_blank'>open-mpi/ompi#13073</a>.

<small>This patch isn't going to work.  The problem is by the time the ompi_mpi_instance_cleanup_pml is invoked the PML framework has already been closed.  For some reason this happens to work for OB1 PML.  Not sure exactly why that is yet....</small>

<a href='https://github.com/open-mpi/ompi/pull/13073' target='_blank'>View Comment</a>