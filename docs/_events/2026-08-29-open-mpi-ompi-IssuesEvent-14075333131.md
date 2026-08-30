---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/7818666?"
user: hppritcha
date: 2026-08-29
repo_name: open-mpi/ompi
html_url: https://github.com/open-mpi/ompi/issues/14348
repo_url: https://github.com/open-mpi/ompi
---

<a href='https://github.com/hppritcha' target='_blank'>hppritcha</a> open issue <a href='https://github.com/open-mpi/ompi/issues/14348' target='_blank'>open-mpi/ompi#14348</a>.

<p>Install MPI ABI into separate prefix</p><small>Open MPI (head of the main branch) installs the header file for the new MPI ABI into `$prefix/include/standard_abi`, while installing OpenMPI ABI header file into `$prefix/include`. Since both header files are called `mpi.h` this is confusing and dangerous; if `$prefix/include` accidentally ends up on the include path then one might accidentally build against the wrong ABI....</small><a href='https://github.com/open-mpi/ompi/issues/14348' target='_blank'>View Comment</a>