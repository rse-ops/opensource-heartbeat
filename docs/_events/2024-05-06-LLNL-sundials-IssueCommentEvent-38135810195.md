---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5669480?"
user: balos1
date: 2024-05-06
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/464
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/balos1' target='_blank'>balos1</a> commented on issue <a href='https://github.com/LLNL/sundials/issues/464' target='_blank'>LLNL/sundials#464</a>.

<small>What CMake version are you using? As of SUNDIALS 7, when you build SUNDIALS with MPI enabled all of SUNDIALS requires MPI because of the new `SUNComm` (so that is why the symbol is required). However, CMake should be adding the `MPI::MPI_CXX` target in and thus the MPI libraries should be getting linked to (even though youre compiling with `g++`). In older CMake versions it did a bad job of propagating things related to MPI correctly.  ...</small>

<a href='https://github.com/LLNL/sundials/issues/464' target='_blank'>View Comment</a>