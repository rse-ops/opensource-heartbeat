---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/7818666?"
user: hppritcha
date: 2022-11-16
repo_name: open-mpi/ompi
html_url: https://github.com/open-mpi/ompi/issues/11084
repo_url: https://github.com/open-mpi/ompi
---

<a href='https://github.com/hppritcha' target='_blank'>hppritcha</a> open issue <a href='https://github.com/open-mpi/ompi/issues/11084' target='_blank'>open-mpi/ompi#11084</a>.

<p>accelerator framework: cuda component assumes application initializes CUDA prior to calling MPI_init</p><small>I'm not sure if this is a bug or a feature, but in testing the accelerator framework work on a system with Nvidia GPUS, I noticed that the osu_mbw_mr test (the 5.8 version of OSU benchmarks) fails using cuda allocated buffers.  The problem is that the cuda component. doesn't get initialized, so the address checker code is not employed.  The other mpi/pt2pt tests initialize CUDA before calling MPI_Init and don't see this problem....</small><a href='https://github.com/open-mpi/ompi/issues/11084' target='_blank'>View Comment</a>