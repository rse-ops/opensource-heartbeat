---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-03-28
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/49698
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/pull/49698' target='_blank'>spack/spack#49698</a>.

<small>Am I reading this right that if you do `g++ -x c`, this will actually change the command to be executed to `SPACK_CC` and thus `gcc` rather than `g++`?  While I'm 100% behind the idea that nobody should do that, invoking `g++ -x c` and `gcc` are different, and  the reverse as well.  The language inference makes total sense to me, but the command selection is a concern, especially if that means selecting a compiler from an entirely different family due to compilers as deps....</small>

<a href='https://github.com/spack/spack/pull/49698' target='_blank'>View Comment</a>