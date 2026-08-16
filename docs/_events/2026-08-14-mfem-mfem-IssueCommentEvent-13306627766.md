---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/17843342?"
user: vladotomov
date: 2026-08-14
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/5361
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/vladotomov' target='_blank'>vladotomov</a> commented on issue <a href='https://github.com/mfem/mfem/pull/5361' target='_blank'>mfem/mfem#5361</a>.

<small>@camierjs the suggested refactor is complete, which also updates the existing code for `DeviceConformingProlongationOperator`. I ran the GPU unit tests with `hip`, some of which use the `MultTranspose`, but I don't think anything there tests the `Mult()`. Hopefully the examples and miniapps will show if something is wrong....</small>

<a href='https://github.com/mfem/mfem/pull/5361' target='_blank'>View Comment</a>