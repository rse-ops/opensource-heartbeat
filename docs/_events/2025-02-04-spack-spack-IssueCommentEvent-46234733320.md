---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-02-04
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/48865
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/issues/48865' target='_blank'>spack/spack#48865</a>.

<small>The `TargetConditionals.h` include is hidden behind including `sanitizer_platform.h`, which pulls it in as long as `__APPLE__` is defined.  I'm really not sure how this could happen, especially with the apple clang used to do the compile, maybe somehow the target triple isn't what it should be?...</small>

<a href='https://github.com/spack/spack/issues/48865' target='_blank'>View Comment</a>