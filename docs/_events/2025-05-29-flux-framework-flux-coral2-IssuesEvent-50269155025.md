---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/20071770?"
user: jameshcorbett
date: 2025-05-29
repo_name: flux-framework/flux-coral2
html_url: https://github.com/flux-framework/flux-coral2/issues/364
repo_url: https://github.com/flux-framework/flux-coral2
---

<a href='https://github.com/jameshcorbett' target='_blank'>jameshcorbett</a> open issue <a href='https://github.com/flux-framework/flux-coral2/issues/364' target='_blank'>flux-framework/flux-coral2#364</a>.

<p>Allow rabbit jobs to tolerate loss of some rabbits and compute nodes during prolog</p><small>@behlendorf recently found that with large rabbit jobs, he was frequently finding that one or two rabbits would fail to create their file systems, or one or two compute nodes would fail to mount. This was a persistent problem, even with all the recent changes to mark nodes as `badrabbit` if they fail to mount. Perhaps this is because not many other rabbit jobs had been submitted, which might have helped filter out some of the bad nodes, or perhaps at that scale it simply becomes likely that something will fail; in any case, it would be useful if the rabbit prolog could proceed in spite of some user-specified number of failures. For example, a user might specify that they want 5050 nodes, and can tolerate the loss of 50 of them, or something similar....</small><a href='https://github.com/flux-framework/flux-coral2/issues/364' target='_blank'>View Comment</a>