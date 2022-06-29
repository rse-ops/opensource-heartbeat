---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-06-28
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/31214
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/issues/31214' target='_blank'>spack/spack#31214</a>.

<small>Sadly the split and quote method does not work, because it breaks things like `spack spec coreutils 'cflags=-O3 -g'` from the command line.  If that goes away, then `spack spec 'coreutils cflags="-O3 -g"'` breaks, and that's required by existing tests to work.  I'm starting to become convinced that we need a coherent policy for how this is supposed to behave we can implement, because at the moment quoted arguments do not work adequately without embedded quotes....</small>

<a href='https://github.com/spack/spack/issues/31214' target='_blank'>View Comment</a>