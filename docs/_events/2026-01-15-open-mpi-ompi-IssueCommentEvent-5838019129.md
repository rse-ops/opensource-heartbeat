---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/7818666?"
user: hppritcha
date: 2026-01-15
repo_name: open-mpi/ompi
html_url: https://github.com/open-mpi/ompi/issues/12979
repo_url: https://github.com/open-mpi/ompi
---

<a href='https://github.com/hppritcha' target='_blank'>hppritcha</a> commented on issue <a href='https://github.com/open-mpi/ompi/issues/12979' target='_blank'>open-mpi/ompi#12979</a>.

<small>some notes on this.  this doesn't seem to be a problem with partial finalization in some ranks verses others.  when the hang occurs I observe some process stuck in waiting for completion of the PMIx_fence_nb near the beginning of finalization while others are stuck in some waitall (on several hundred requests per call) within the application....</small>

<a href='https://github.com/open-mpi/ompi/issues/12979' target='_blank'>View Comment</a>