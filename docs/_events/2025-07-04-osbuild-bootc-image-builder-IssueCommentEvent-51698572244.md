---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/16666742?"
user: imguoguo
date: 2025-07-04
repo_name: osbuild/bootc-image-builder
html_url: https://github.com/osbuild/bootc-image-builder/pull/963
repo_url: https://github.com/osbuild/bootc-image-builder
---

<a href='https://github.com/imguoguo' target='_blank'>imguoguo</a> commented on issue <a href='https://github.com/osbuild/bootc-image-builder/pull/963' target='_blank'>osbuild/bootc-image-builder#963</a>.

<small>> Fwiw, I submited an RFC patch to the qemu-devel mailinglist that return "0" unconditionally for the set_robust_list() syscall. When I do this locally the podman locking works so I'm 90% confident that it solves the problem. I have no sense in how likely it is that the patch gets accepted though (my guess is not very likely), its arguably wrong but also in practice glibc does not care - it is a risk for non-glibc threading implementations though which would be a good reason to reject it (otoh most languages like rust/java use glibc it seems, go does not use set_robust_list and musl https://git.musl-libc.org/cgit/musl/tree/src/thread/pthread_mutex_trylock.c#n30 also does not check the return code ]...</small>

<a href='https://github.com/osbuild/bootc-image-builder/pull/963' target='_blank'>View Comment</a>