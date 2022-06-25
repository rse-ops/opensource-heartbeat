---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-06-24
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/30545
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/issues/30545' target='_blank'>spack/spack#30545</a>.

<small>Yes, I think that's sufficient.  I reworked the generate_commit_lookup to chain down into inner versions already, but it needs the reordering fix.  The tuple version comparisons do need to use -inf and inf for none at start and end, in fact I think my local prototype currently does that, the one above was buggy and had them reversed, good catch!...</small>

<a href='https://github.com/spack/spack/issues/30545' target='_blank'>View Comment</a>