---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/13971568?"
user: becker33
date: 2026-02-19
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/51960
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/becker33' target='_blank'>becker33</a> commented on issue <a href='https://github.com/spack/spack/pull/51960' target='_blank'>spack/spack#51960</a>.

<small>I think this change is going to make adding the per-package locking for the new installer very difficult. I think you're going to need access to the overwrite information when you approach the install for each package, because an intervening process may have installed it between when you constructed the `BuildGraph` and when the build gets to that install. I think each call to `worker_function` needs to know whether it is an overwrite build and what time it was labelled as an overwrite build, so that it can accept if another process already overwrote in the meantime....</small>

<a href='https://github.com/spack/spack/pull/51960' target='_blank'>View Comment</a>