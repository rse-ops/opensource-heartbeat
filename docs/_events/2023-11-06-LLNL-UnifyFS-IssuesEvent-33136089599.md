---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/12384825?"
user: CamStan
date: 2023-11-06
repo_name: LLNL/UnifyFS
html_url: https://github.com/LLNL/UnifyFS/issues/72
repo_url: https://github.com/LLNL/UnifyFS
---

<a href='https://github.com/CamStan' target='_blank'>CamStan</a> closed issue <a href='https://github.com/LLNL/UnifyFS/issues/72' target='_blank'>LLNL/UnifyFS#72</a>.

<p>Improve error handling if /dev/shm too small</p><small>In #59 it was reported that an application crashed with SIGBUS if /dev/shm was configured with insufficient space. On the mailing list it was suggested that this case could be detected and reported more gracefully if we replace the use of `ftruncate()` with `fallocate()`, although that would sacrifice portability since `fallocate()` is Linux-specific. @adammoody also pointed out that we'd need to examine how memory pages are assigned to NUMA banks with `fallocate()`....</small><a href='https://github.com/LLNL/UnifyFS/issues/72' target='_blank'>View Comment</a>