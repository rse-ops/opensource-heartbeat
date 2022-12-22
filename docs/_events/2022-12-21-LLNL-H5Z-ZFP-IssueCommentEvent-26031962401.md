---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2022-12-21
repo_name: LLNL/H5Z-ZFP
html_url: https://github.com/LLNL/H5Z-ZFP/issues/95
repo_url: https://github.com/LLNL/H5Z-ZFP
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/LLNL/H5Z-ZFP/issues/95' target='_blank'>LLNL/H5Z-ZFP#95</a>.

<small>Ok, I think I may know the issue now that I've written the above description. I think the issue is that when the filter writes ZFP's header to the dataset's `unsigned int cd_vals[6]`, those 24 bytes are being treated as a sequence of bytes by ZFP. Ok, thats fine. But, in a mixed endian context, those bytes get byte-swapped for endianness when ZFP is probably expecting that they don't get byte swapped....</small>

<a href='https://github.com/LLNL/H5Z-ZFP/issues/95' target='_blank'>View Comment</a>