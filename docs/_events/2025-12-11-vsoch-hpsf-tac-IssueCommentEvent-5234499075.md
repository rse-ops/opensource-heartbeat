---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2025-12-11
repo_name: vsoch/hpsf-tac
html_url: https://github.com/vsoch/hpsf-tac/pull/1
repo_url: https://github.com/vsoch/hpsf-tac
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/vsoch/hpsf-tac/pull/1' target='_blank'>vsoch/hpsf-tac#1</a>.

<small>Depending on what you need, it also often works well to include just user-mode flux (core and sched is often enough) inside the container, then in the allocation use srun to launch a flux instance with all brokers running in the container with your optimizer running as the initial program. It requires changing the container, where the sidecar does not, but avoids the need for kubernetes to use the operator. It