---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-10-13
repo_name: rsmpi/rsmpi
html_url: https://github.com/rsmpi/rsmpi/issues/133
repo_url: https://github.com/rsmpi/rsmpi
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/rsmpi/rsmpi/issues/133' target='_blank'>rsmpi/rsmpi#133</a>.

<small>Does our definition of safe mean unenforceable dependence on other ranks? In that case, normal and synchronous sends would also be unsafe, while `Isend` could be safe (but waiting on the request would not be). And if that's the case, `Irecv` could also be safe (it's just saying "you can write into this suitably sized buffer") but the wait again would be unsafe. Those rules feel awkward....</small>

<a href='https://github.com/rsmpi/rsmpi/issues/133' target='_blank'>View Comment</a>