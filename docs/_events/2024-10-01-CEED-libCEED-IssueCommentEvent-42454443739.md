---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/62483075?"
user: eliasboegel
date: 2024-10-01
repo_name: CEED/libCEED
html_url: https://github.com/CEED/libCEED/issues/1677
repo_url: https://github.com/CEED/libCEED
---

<a href='https://github.com/eliasboegel' target='_blank'>eliasboegel</a> commented on issue <a href='https://github.com/CEED/libCEED/issues/1677' target='_blank'>CEED/libCEED#1677</a>.

<small>Perhaps the larger problem is informing `cc` about the include directory for libCEED such that `ceed.h` is accessible in the QFunction source file. That seems especially difficult (or impossible?) if libCEED was built by the bindings. Essentially, `cc` would need to be supplied _in the users `build.rs`_ with a path to `target/{profile}/build/libceed-sys-{hash}/out/include/` but I don't know any way to automatically retrieve the right hash, nevermind a way that is simple enough that a user can be reasonably expected to figure it out. I saw in the `libceed-sys` readme that you've had a similar problem in the past?...</small>

<a href='https://github.com/CEED/libCEED/issues/1677' target='_blank'>View Comment</a>