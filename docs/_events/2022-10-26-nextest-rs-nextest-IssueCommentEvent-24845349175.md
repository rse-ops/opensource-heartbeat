---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-10-26
repo_name: nextest-rs/nextest
html_url: https://github.com/nextest-rs/nextest/issues/605
repo_url: https://github.com/nextest-rs/nextest
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/nextest-rs/nextest/issues/605' target='_blank'>nextest-rs/nextest#605</a>.

<small>Thanks! I'll give that a try. Does nextest have a concept of tests needing more than one "slot" of parallelism? I ask because parallel jobs exhibit severe slow-down when oversubscribed (more processes than logical cores). This could be handled instead by a resource manager in the test harness that gently blocks each job until enough slots are available to `mpiexec`. (Some environments have external resource managers, but they're too much hassle for each contributor to configure and generally increase single job latency.)...</small>

<a href='https://github.com/nextest-rs/nextest/issues/605' target='_blank'>View Comment</a>