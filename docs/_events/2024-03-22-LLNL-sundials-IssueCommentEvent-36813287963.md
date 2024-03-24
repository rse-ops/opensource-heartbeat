---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/15018133?"
user: gardner48
date: 2024-03-22
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/pull/445
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/gardner48' target='_blank'>gardner48</a> commented on issue <a href='https://github.com/LLNL/sundials/pull/445' target='_blank'>LLNL/sundials#445</a>.

<small>Just specifying the minimum is easier. I think we should explain in this [section](https://sundials.readthedocs.io/en/latest/sundials/Install_link.html#using-sundials-as-a-third-party-library-in-other-cmake-projects) that starting with version `x.z.y.` the version number provided to `find_package` will be treated as the minimum required and any newer version found will be marked as compatible. If users need to limit the range, then should use the version range feature to limit the range of acceptable versions....</small>

<a href='https://github.com/LLNL/sundials/pull/445' target='_blank'>View Comment</a>