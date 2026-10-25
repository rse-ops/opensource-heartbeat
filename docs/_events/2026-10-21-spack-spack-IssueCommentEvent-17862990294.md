---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/13971568?"
user: becker33
date: 2026-10-21
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/52779
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/becker33' target='_blank'>becker33</a> commented on issue <a href='https://github.com/spack/spack/pull/52779' target='_blank'>spack/spack#52779</a>.

<small>The key bit of the use case is that you're passing a concrete environment from a user who added a variant to a user who did not take the new variant. The goal is (in combination with the fact you can already modify the namespace of a concrete spec) make the concrete spec that includes the variant usable with a repo that does not include the variant. And if the variant exists on the spec, it will fail variant validation. Among other places, variant validation is run on any concrete spec that is included in an environment when the rest of the environment is concretized (if unify != False)...</small>

<a href='https://github.com/spack/spack/pull/52779' target='_blank'>View Comment</a>