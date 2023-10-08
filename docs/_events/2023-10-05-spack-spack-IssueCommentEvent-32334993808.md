---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2023-10-05
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/35737
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/pull/35737' target='_blank'>spack/spack#35737</a>.

<small>Overriding CXX seems especially unfortunate to be honest.  It's not wrong in a sense, but it's really, really wrong in another since it's supposed to be the HIP compiler and not necessarily the C or C++ compilers (though maybe the C++ compiler :facepalm:).  That's a nasty compilers as deps problem really, @tgamblin, @alalazo, @becker33, any thoughts on handling language *dialect* deps? In a sense hip is a language, the compilers and cmake treat it that way, but it's also a dialect of C++, so it should be able to provide both, and *maybe* override both, but allow C++ to come from something else as well in the same project....</small>

<a href='https://github.com/spack/spack/pull/35737' target='_blank'>View Comment</a>