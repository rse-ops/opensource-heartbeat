---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2024-01-20
repo_name: LLNL/H5Z-ZFP
html_url: https://github.com/LLNL/H5Z-ZFP/issues/133
repo_url: https://github.com/LLNL/H5Z-ZFP
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/LLNL/H5Z-ZFP/issues/133' target='_blank'>LLNL/H5Z-ZFP#133</a>.

<small>If we store an additional bit of info in the H5Z-ZFP header, then I think we should design things to *require* 8-bit on writes by default but allow user to override this default allowing non-8-bit word stream on writes. This would mean adding a property to the properties interface and utilizing a currently unused bit in the generic interface. By default H5Z-ZFP would behave as it currently does, erroring in `H5Dcreate()` if ZFP was configured for something other than 8-bit streams....</small>

<a href='https://github.com/LLNL/H5Z-ZFP/issues/133' target='_blank'>View Comment</a>