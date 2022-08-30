---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2022-08-29
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3129
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3129' target='_blank'>mfem/mfem#3129</a>.

<small>The way MFEM is compiled when CUDA and MPI are enabled is that we tell `nvcc` (defined by `CUDA_CXX`) to call the MPI compiler (defined by `MPICXX`) for host compilation via the `-ccbin` flag. Thus, if you set `MPICXX=CC` then `nvcc` will call `CC` for host compilation....</small>

<a href='https://github.com/mfem/mfem/issues/3129' target='_blank'>View Comment</a>