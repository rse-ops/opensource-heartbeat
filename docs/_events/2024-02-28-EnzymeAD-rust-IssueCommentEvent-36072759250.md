---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2024-02-28
repo_name: EnzymeAD/rust
html_url: https://github.com/EnzymeAD/rust/issues/79
repo_url: https://github.com/EnzymeAD/rust
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/EnzymeAD/rust/issues/79' target='_blank'>EnzymeAD/rust#79</a>.

<small>Well, in standard mode, precompiled `libLLVMEnzyme-17.so` will be shipped in their binary distribution so the CMake files (and a C/C++ compiler for that matter) won't be needed. It is useful for anyone who wants to _develop_ autodiff functionality since they'd like to be able to upgrade Enzyme without first needing to recompile libLLVM. We might be better off running our own CI to create weekly-ish builds that include CMake files, but not trying to change how upstream does it. If it's just the three people in this thread, we're probably accustomed to building libLLVM so this is not so urgent....</small>

<a href='https://github.com/EnzymeAD/rust/issues/79' target='_blank'>View Comment</a>