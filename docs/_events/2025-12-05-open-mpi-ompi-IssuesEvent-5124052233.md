---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/7818666?"
user: hppritcha
date: 2025-12-05
repo_name: open-mpi/ompi
html_url: https://github.com/open-mpi/ompi/issues/14
repo_url: https://github.com/open-mpi/ompi
---

<a href='https://github.com/hppritcha' target='_blank'>hppritcha</a> closed issue <a href='https://github.com/open-mpi/ompi/issues/14' target='_blank'>open-mpi/ompi#14</a>.

<p>Allow F90 MPI_BUFFER_DETACH to return correct pointer</p><small>The current F77 MPI_BUFFER_DETACH implementation does not return the detached buffer pointer to the caller -- it simply does not make sense to do this in F77 because a) you can't get it, b) pointer implementations between compilers seem to differ, and c) even among the F77 compilers that do support pointers, you can't compare or use the pointer in a meaningful way.  There are two precedents that support this interpretation: LAM/MPI and CT6 both do not return the pointer to F77 callers....</small><a href='https://github.com/open-mpi/ompi/issues/14' target='_blank'>View Comment</a>