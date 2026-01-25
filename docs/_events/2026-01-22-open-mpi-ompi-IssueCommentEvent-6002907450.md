---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/7818666?"
user: hppritcha
date: 2026-01-22
repo_name: open-mpi/ompi
html_url: https://github.com/open-mpi/ompi/issues/12979
repo_url: https://github.com/open-mpi/ompi
---

<a href='https://github.com/hppritcha' target='_blank'>hppritcha</a> commented on issue <a href='https://github.com/open-mpi/ompi/issues/12979' target='_blank'>open-mpi/ompi#12979</a>.

<small>The application uses persistent send/recv requests with the comm pattern being an all-to-one pattern.  The individual messages for the problem suggested above are about 40000 bytes in size when using 60 ranks.   I'm seeing the hang for fewer than 64 procs.  The behavior appears to be that the target rank (0) does receive all its messages but some of the senders do not "think" that all of their sends are complete.  Again this appears to be btl-sm specific.  turning off the fast boxes does not appear to help.  investigation continues......</small>

<a href='https://github.com/open-mpi/ompi/issues/12979' target='_blank'>View Comment</a>