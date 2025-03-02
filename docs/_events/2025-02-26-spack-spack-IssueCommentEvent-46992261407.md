---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-02-26
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/46416
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/pull/46416' target='_blank'>spack/spack#46416</a>.

<small>I'm not really fond of this as an idea, and especially not as a name for the variant.  It's building LLVM the package, but doesn't provide LLVM, which prevents the use of LLVM in the same package DAG if this variant is selected. It would be less disruptive if it were a separate package, though I do understand that's a harder rework.  If this needs to go in this way, please make the variant self-explanatory. The current name `standalone` implies to me that it builds a standalone LLVM (I would expect that to mean self-hosted on the llvm libc or similar). Perhaps `openmp_libraries_only`?...</small>

<a href='https://github.com/spack/spack/pull/46416' target='_blank'>View Comment</a>