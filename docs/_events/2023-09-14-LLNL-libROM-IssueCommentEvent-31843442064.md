---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2023-09-14
repo_name: LLNL/libROM
html_url: https://github.com/LLNL/libROM/pull/237
repo_url: https://github.com/LLNL/libROM
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/LLNL/libROM/pull/237' target='_blank'>LLNL/libROM#237</a>.

<small>The difference between these functions is that `GetNumRows` calls a hypre function, whereas `NumRows` simply returns `height` in the base class `Operator`. I guess the hypre call has some complication in the python version, and maybe that needs to be resolved in pymfem. It is not clear from the header files whether `GetNumRows` and `NumRows` should always return the same number, but it looks like the `HypreParMatrix` constructors set `height` to `GetNumRows`, so I think there should not be any difference. At least the regression tests passed....</small>

<a href='https://github.com/LLNL/libROM/pull/237' target='_blank'>View Comment</a>