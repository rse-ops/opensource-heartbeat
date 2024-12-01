---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-11-25
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/47739
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/pull/47739' target='_blank'>spack/spack#47739</a>.

<small>In principle gcc can be built without libz, but I'm not sure that's better... It's a bit of a nasty circular dependence.  We could make it so that the gcc-runtime package depends on libz, and hack libz not to depend on gcc-runtime, but we'd need to track which libc it was built for some other way.  Honestly I'm not sure how we manage that....</small>

<a href='https://github.com/spack/spack/pull/47739' target='_blank'>View Comment</a>