---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/274859?"
user: chu11
date: 2022-08-01
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4456
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/chu11' target='_blank'>chu11</a> open issue <a href='https://github.com/flux-framework/flux-core/issues/4456' target='_blank'>flux-framework/flux-core#4456</a>.

<p>content-{sqlite,files,s3}: register backing store after registering services</p><small>While working on #4267, realized that ENOSYS errors encountered are due to the fact that the `content-{sqlite,files,s3}` modules all register themselves as backing stores BEFORE registering their services.  This makes it so that `cache_flush()` and similar things in the `content-cache` cannot work during the registration process....</small><a href='https://github.com/flux-framework/flux-core/issues/4456' target='_blank'>View Comment</a>