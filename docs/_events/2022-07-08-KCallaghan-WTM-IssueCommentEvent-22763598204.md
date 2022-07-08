---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-07-08
repo_name: KCallaghan/WTM
html_url: https://github.com/KCallaghan/WTM/pull/64
repo_url: https://github.com/KCallaghan/WTM
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/KCallaghan/WTM/pull/64' target='_blank'>KCallaghan/WTM#64</a>.

<small>So for BDF1 (backward Euler), the calculation looks like $H_t = \frac{H(h^{n+1}) - H(h^n)}{\Delta t}$ and since you write $H(\cdot) = 100$ uniformly, these cancel exactly and you get $H_t = 0$. You get nontrivial $H_t$ if you apply this patch. (Feel free to give me push access if you'd rather I just push these changes.)...</small>

<a href='https://github.com/KCallaghan/WTM/pull/64' target='_blank'>View Comment</a>