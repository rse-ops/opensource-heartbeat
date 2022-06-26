---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2022-06-26
repo_name: flux-framework/flux-pam
html_url: https://github.com/flux-framework/flux-pam/pull/1
repo_url: https://github.com/flux-framework/flux-pam
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-pam/pull/1' target='_blank'>flux-framework/flux-pam#1</a>.

<small>Oh oops, that was sloppy. `pam_wrapper` is from the [cwrap](https://cwrap.org/pam_wrapper.html) project (part of samba), and allows simulating running the PAM stack from a standalone application without modifying the actual PAM stack. It is currently pulled in to CI, and `make check` should be disabled if `libpamtest.so` isn't found at configure time....</small>

<a href='https://github.com/flux-framework/flux-pam/pull/1' target='_blank'>View Comment</a>