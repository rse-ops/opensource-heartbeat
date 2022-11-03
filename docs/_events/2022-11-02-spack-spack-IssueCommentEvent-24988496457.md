---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-11-02
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/32253
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/pull/32253' target='_blank'>spack/spack#32253</a>.

<small>This should work with rewiring again now.  There's a case that we neglected to consider in rewiring, where the package being rewired needs to replace the paths *of other packages* that are not having their hashes replaced and thus we can't frankenhash.  For right now, I have the check failing these only if the prefix is followed immediately by a null byte, because that's the only case when that suffix could have been reused.  For all the cases we test in the repository, that works out fine, but I have no way to predict how often that will be a problem for rewiring in the wild.  We should probably consider solutions to that for the future....</small>

<a href='https://github.com/spack/spack/pull/32253' target='_blank'>View Comment</a>