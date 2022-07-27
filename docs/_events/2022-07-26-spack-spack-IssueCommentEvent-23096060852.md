---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-07-26
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/31739
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/pull/31739' target='_blank'>spack/spack#31739</a>.

<small>@tgamblin, @becker33 I think I've updated everything that can reasonably be done here.  The gmake package overrides the version used, but leaves the base one there so we don't break the world.  I went to add a `bmake` to the bsd make package, but it currently doesn't build for me under spack (the exact same command outside spack works, so I have no idea why) but we didn't have that before so it's not terribly important....</small>

<a href='https://github.com/spack/spack/pull/31739' target='_blank'>View Comment</a>