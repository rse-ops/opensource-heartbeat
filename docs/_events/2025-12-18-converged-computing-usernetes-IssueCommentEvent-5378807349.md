---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-12-18
repo_name: converged-computing/usernetes
html_url: https://github.com/converged-computing/usernetes/pull/2
repo_url: https://github.com/converged-computing/usernetes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/converged-computing/usernetes/pull/2' target='_blank'>converged-computing/usernetes#2</a>.

<small>@AkihiroSuda if you are interested, we were testing calico for usernetes https://github.com/converged-computing/usernetes/tree/test-calico (hoping to not need to set `net.ipv4.conf.default.rp_filter` to 2) and got it deployed (calico pods running), but the connectivity between pods isn't there yet. I think packets are being dropped. Maybe by the kernel (which could be related to that setting still being 2). We were trying to use vxlan although I'm not sure if that is the right path, and if we can test with the rp_filter setting still at 2....</small>

<a href='https://github.com/converged-computing/usernetes/pull/2' target='_blank'>View Comment</a>