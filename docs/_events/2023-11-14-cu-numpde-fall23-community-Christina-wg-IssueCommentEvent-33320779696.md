---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-11-14
repo_name: cu-numpde/fall23-community-Christina-wg
html_url: https://github.com/cu-numpde/fall23-community-Christina-wg/issues/2
repo_url: https://github.com/cu-numpde/fall23-community-Christina-wg
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/cu-numpde/fall23-community-Christina-wg/issues/2' target='_blank'>cu-numpde/fall23-community-Christina-wg#2</a>.

<small>Cool. I would link the paper by DOI and say specifically that you want to set up example 2.2 (isentropic vortex) as a convergence study. I would focus on comparing SharpClaw (high-order "WENO") with classic Clawpack (2nd order) in terms of accuracy and simulation cost. If that goes well, you might add a problem with a shock. I don't think it's necessary to compare with arbitrary other packages, though you'll be able to run this problem out of the box using ceed-fluids (uses a finite element method), reporting execution time and errors. If you add a shock, ceed-fluids will likely do poorly (there is one shock capturing method that might work)....</small>

<a href='https://github.com/cu-numpde/fall23-community-Christina-wg/issues/2' target='_blank'>View Comment</a>