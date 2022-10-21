---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-10-20
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/33248
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/pull/33248' target='_blank'>spack/spack#33248</a>.

<small>It's also aware of weak binding without cgroups, which is what taskset uses.  As long as only one spack install is allowed to actually *build* something at a time, this wont change the risks.  If there's a top-level `make -j 5` that runs multiple concurrent installs that run builds, rather than installing from the binary cache, then it's possible because of misbehaving build systems and linkers ignoring the jobserver, but I don't think we have that case here....</small>

<a href='https://github.com/spack/spack/pull/33248' target='_blank'>View Comment</a>