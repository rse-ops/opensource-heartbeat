---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2023-11-07
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/40825
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/spack/spack/pull/40825' target='_blank'>spack/spack#40825</a>.

<small>@masterleinad, part of the problem with the deal.II failures in CI is probably due the very long paths they use which in turn force CMake (and/or Ninja) to use response files which fail with `nvcc_wrapper`. In a normal build on Polaris, your PR worked fine for me with the spec `dealii+cuda~gmsh cuda_arch=80`. To speedup the build, I disabled `gmsh` -- adding that may also be a part of the reason that CMake (and/or Ninja) starts to use response files, however, the very long paths used in Spack CI may be the main reason....</small>

<a href='https://github.com/spack/spack/pull/40825' target='_blank'>View Comment</a>