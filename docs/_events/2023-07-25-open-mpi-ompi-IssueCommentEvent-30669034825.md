---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/7818666?"
user: hppritcha
date: 2023-07-25
repo_name: open-mpi/ompi
html_url: https://github.com/open-mpi/ompi/pull/11689
repo_url: https://github.com/open-mpi/ompi
---

<a href='https://github.com/hppritcha' target='_blank'>hppritcha</a> commented on issue <a href='https://github.com/open-mpi/ompi/pull/11689' target='_blank'>open-mpi/ompi#11689</a>.

<small>couple of things.  i'll look in to this more when i get back in the office next monday.  second, i had to apply a patch to avoid segfaults inside the ofi btl init method that would occur under certain conditions of procs per node and proc layout, and third the new algorithm is always selecting cxi0 for all ranks on the node.  the node layout is one socket is connected to cxi0 and the other to cxi1. ...</small>

<a href='https://github.com/open-mpi/ompi/pull/11689' target='_blank'>View Comment</a>