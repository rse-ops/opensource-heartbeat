---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/13821049?"
user: CRobeck
date: 2024-01-02
repo_name: llvm/llvm-project
html_url: https://github.com/llvm/llvm-project/issues/71692
repo_url: https://github.com/llvm/llvm-project
---

<a href='https://github.com/CRobeck' target='_blank'>CRobeck</a> commented on issue <a href='https://github.com/llvm/llvm-project/issues/71692' target='_blank'>llvm/llvm-project#71692</a>.

<small>I remember running into this when reserving registers for long branches. We set an initial set of reserved registers and then compact down to the lowest unused ones. At the time it wasn't clear when the latest point we could do that was. It would be good to consolidate that. reserveReg is similar freezeReservedRegs but less of a hammer in terms of recomputing.. That section of code is here:...</small>

<a href='https://github.com/llvm/llvm-project/issues/71692' target='_blank'>View Comment</a>