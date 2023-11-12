---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1105742?"
user: adammoody
date: 2023-11-10
repo_name: hpc/mpifileutils
html_url: https://github.com/hpc/mpifileutils/issues/560
repo_url: https://github.com/hpc/mpifileutils
---

<a href='https://github.com/adammoody' target='_blank'>adammoody</a> commented on issue <a href='https://github.com/hpc/mpifileutils/issues/560' target='_blank'>hpc/mpifileutils#560</a>.

<small>Thanks, @adilger .  I was hoping you might still be following this thread.  The global barrier should ensure that ``sync`` has been called by all ranks before any rank starts to set timestamps.  However, if ``sync`` returns before all data has been written by the servers, then that could lead to the problem that we're seeing....</small>

<a href='https://github.com/hpc/mpifileutils/issues/560' target='_blank'>View Comment</a>