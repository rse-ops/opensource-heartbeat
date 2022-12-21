---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-12-21
repo_name: CEED/libCEED
html_url: https://github.com/CEED/libCEED/pull/1096
repo_url: https://github.com/CEED/libCEED
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/CEED/libCEED/pull/1096' target='_blank'>CEED/libCEED#1096</a>.

<small>Hi @jnclement. I think what remains to be done is pretty simple. I linked parameters from PHASTA above and some of these are mentioned also in `blasius.yaml`. At first pass, I'd just like to see these set for linear, quadratic, and cubic. Rather than trying to create a function for arbitrary order, higher than cubic could just use the cubic value (and we can revisit them when we have reason to run those higher order cases, as we may have a more principled quantitative analysis framework by then). The goal is really just to have reasonable starting values so that inputs (like in the yaml files) don't have to be tuned separately for different basis order....</small>

<a href='https://github.com/CEED/libCEED/pull/1096' target='_blank'>View Comment</a>