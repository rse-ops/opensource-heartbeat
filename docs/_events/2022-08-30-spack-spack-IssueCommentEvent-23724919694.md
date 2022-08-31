---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-08-30
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/31948
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/pull/31948' target='_blank'>spack/spack#31948</a>.

<small>To add a bit of context to the julia musl issue, it shouldn't cause problems here (though we should always test).  The normal glibc thing is that it uses the soname as the cache key in the loading binary, so as long as the soname matches it's all good.  This is what musl does (pythonic pseudocode):...</small>

<a href='https://github.com/spack/spack/pull/31948' target='_blank'>View Comment</a>