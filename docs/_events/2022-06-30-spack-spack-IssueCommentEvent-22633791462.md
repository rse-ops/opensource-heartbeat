---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/299842?"
user: tgamblin
date: 2022-06-30
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/31368
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/tgamblin' target='_blank'>tgamblin</a> commented on issue <a href='https://github.com/spack/spack/pull/31368' target='_blank'>spack/spack#31368</a>.

<small>I don't see anything fundamentally wrong with that, but I'm not sure it covers all the cases.  The ref count not only tells you whether you can uninstall, but also whether you should keep a node in the database (installed or not). I think it still serves the latter purpose in its current form, but wouldn't with this change.  So would *that* logic become more complicated?...</small>

<a href='https://github.com/spack/spack/pull/31368' target='_blank'>View Comment</a>