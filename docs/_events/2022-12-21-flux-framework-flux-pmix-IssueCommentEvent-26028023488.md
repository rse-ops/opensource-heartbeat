---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/741970?"
user: grondo
date: 2022-12-21
repo_name: flux-framework/flux-pmix
html_url: https://github.com/flux-framework/flux-pmix/issues/70
repo_url: https://github.com/flux-framework/flux-pmix
---

<a href='https://github.com/grondo' target='_blank'>grondo</a> commented on issue <a href='https://github.com/flux-framework/flux-pmix/issues/70' target='_blank'>flux-framework/flux-pmix#70</a>.

<small>I've seen valgrind report false positive for uninitialized bytes when some optimization or other platform dependent thing was actually causing initialization that valigrind couldn't see. Not sure that is the case here, but by using `memset` you could have hinted to valgrind that the bytes are indeed initialized....</small>

<a href='https://github.com/flux-framework/flux-pmix/issues/70' target='_blank'>View Comment</a>