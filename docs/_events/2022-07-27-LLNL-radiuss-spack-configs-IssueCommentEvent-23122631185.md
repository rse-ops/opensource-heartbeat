---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-07-27
repo_name: LLNL/radiuss-spack-configs
html_url: https://github.com/LLNL/radiuss-spack-configs/pull/38
repo_url: https://github.com/LLNL/radiuss-spack-configs
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/LLNL/radiuss-spack-configs/pull/38' target='_blank'>LLNL/radiuss-spack-configs#38</a>.

<small>Fair enough, it certainly should work, especially with externals set up appropriately.  The trick is that spack sets things up per-package, and AMD decomposed ROCM into a great deal of packages, both in spack and in RPMs and debs.  As long as they're all tied in, it should just work, and that's where we're trying to get to. This PR is a good example of the problem though, ROCPrim used to come in by default with something else we already had in externals, but got re-packaged and no longer comes in that way.  It broke our spack package as well.  Hopefully once we get over the bumps in the next couple of ROCM releases this will all stabilize a bit more and get us where we need to be....</small>

<a href='https://github.com/LLNL/radiuss-spack-configs/pull/38' target='_blank'>View Comment</a>