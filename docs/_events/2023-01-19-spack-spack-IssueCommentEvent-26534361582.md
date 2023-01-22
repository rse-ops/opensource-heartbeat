---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2023-01-19
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/35017
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/issues/35017' target='_blank'>spack/spack#35017</a>.

<small>Oof... yes, we might want to do that.  I say oof because there are potentially a *lot* of corner cases here.  The major reason is intel and PGI, especially icc's `-ax` flag to add runtime-dispatched architecture specialization targets.  The recent issues with OpenBLAS make me think that controlling this, or at least being made immediately aware of it so we can decide whether we take theirs or ours, tell me this is a really good idea though....</small>

<a href='https://github.com/spack/spack/issues/35017' target='_blank'>View Comment</a>