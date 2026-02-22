---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/7818666?"
user: hppritcha
date: 2026-02-19
repo_name: open-mpi/ompi
html_url: https://github.com/open-mpi/ompi/pull/13734
repo_url: https://github.com/open-mpi/ompi
---

<a href='https://github.com/hppritcha' target='_blank'>hppritcha</a> commented on issue <a href='https://github.com/open-mpi/ompi/pull/13734' target='_blank'>open-mpi/ompi#13734</a>.

<small>```ompi_rte_init``` is only called within ```ompi_mpi_instance_init``` which can in principle be invoked via multiple threads concurrently since MPI_Session_init (correctly recalled by @rch54) can be called by individual threads.  totally different from MPI_Init/MPI_INit_thread and one of the reasons for its presence in the standard....</small>

<a href='https://github.com/open-mpi/ompi/pull/13734' target='_blank'>View Comment</a>