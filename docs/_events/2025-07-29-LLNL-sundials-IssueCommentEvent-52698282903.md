---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/15018133?"
user: gardner48
date: 2025-07-29
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/753
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/gardner48' target='_blank'>gardner48</a> commented on issue <a href='https://github.com/LLNL/sundials/issues/753' target='_blank'>LLNL/sundials#753</a>.

<small>Hi @mottelet, between versions 6.6 and 7.4 there have not been any changes to the projection capability in CVODE. The error handling across SUNDIALS was updated in v7 however, this should not have changed any of the return codes from CVODE. There were some fixes related to the stop time in versions [v6.6.1](https://github.com/LLNL/sundials/blob/main/CHANGELOG.md#changes-to-sundials-in-release-661) and [v6.7.0](https://github.com/LLNL/sundials/blob/main/CHANGELOG.md#changes-to-sundials-in-release-670) that could be related to what you are seeing. Before these fixes, it was possible that CVODE would reach a stop time but return `CV_SUCCESS` instead of `CV_TSTOP_RETURN` when the output time and the stop time are the same. ...</small>

<a href='https://github.com/LLNL/sundials/issues/753' target='_blank'>View Comment</a>