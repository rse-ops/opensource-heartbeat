---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-08-06
repo_name: EnzymeAD/Enzyme
html_url: https://github.com/EnzymeAD/Enzyme/pull/767
repo_url: https://github.com/EnzymeAD/Enzyme
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/EnzymeAD/Enzyme/pull/767' target='_blank'>EnzymeAD/Enzyme#767</a>.

<small>Cool, so I think to make use of that, one would need a context (could hold the start of the buffer that was preallocated on the host) and an index (like a thread id, but I think it's better to allow the caller to compute an application-relevant index rather than having the allocator directly checking `threadIdx` and `blockIdx`, which requires making assumptions). Is that what you're thinking?...</small>

<a href='https://github.com/EnzymeAD/Enzyme/pull/767' target='_blank'>View Comment</a>