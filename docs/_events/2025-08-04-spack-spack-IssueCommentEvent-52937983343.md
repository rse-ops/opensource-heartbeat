---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/299842?"
user: tgamblin
date: 2025-08-04
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/51061
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/tgamblin' target='_blank'>tgamblin</a> commented on issue <a href='https://github.com/spack/spack/issues/51061' target='_blank'>spack/spack#51061</a>.

<small>@haampie We discussed a number of solutions for this, and I don't see an easy one.  The proposal is *not* to ignore the provenance -- it's to keep it but build one version *as* another. As you say, when you tell Spack to treat sources as a particular version, you are doing the same thing -- assigning a version.  In fact, you could already do what is in this PR if you had the git repo for every version.  We're simply extending it to work for releases/tarballs instead of just git versions....</small>

<a href='https://github.com/spack/spack/issues/51061' target='_blank'>View Comment</a>