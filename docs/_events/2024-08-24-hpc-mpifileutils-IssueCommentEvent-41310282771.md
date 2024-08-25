---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1105742?"
user: adammoody
date: 2024-08-24
repo_name: hpc/mpifileutils
html_url: https://github.com/hpc/mpifileutils/issues/579
repo_url: https://github.com/hpc/mpifileutils
---

<a href='https://github.com/adammoody' target='_blank'>adammoody</a> commented on issue <a href='https://github.com/hpc/mpifileutils/issues/579' target='_blank'>hpc/mpifileutils#579</a>.

<small>Thanks for the report, @samlor .  dbz2 writes to a single shared file from multiple processes.  For correctness, it requires a POSIX-compliant parallel file system like Lustre or IBM's Spectrum Scale.  In particular, many NFS file systems are not POSIX-compliant....</small>

<a href='https://github.com/hpc/mpifileutils/issues/579' target='_blank'>View Comment</a>