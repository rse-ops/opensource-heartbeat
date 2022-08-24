---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-08-23
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/32183
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/pull/32183' target='_blank'>spack/spack#32183</a>.

<small>Ok, bootstrap test rework now in, uses the hostedtoolcache with my tmpconfig wrapper to test bootstrapping on all pythons in the same image. Cuts bootstrap builds on macOS and Ubuntu from 5 each to 1 each, and ~2 minutes per os/py version combo to ~3 minutes per OS. Not quite as fast, assuming max concurrency, but uses 12 less runners to get the bootstrap done almost as fast. Main cost in those is in pulling all of spack, so pulling it once rather than 5 times helps a whole lot. ...</small>

<a href='https://github.com/spack/spack/pull/32183' target='_blank'>View Comment</a>