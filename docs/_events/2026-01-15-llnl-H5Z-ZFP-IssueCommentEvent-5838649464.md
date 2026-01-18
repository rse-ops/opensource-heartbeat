---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2026-01-15
repo_name: llnl/H5Z-ZFP
html_url: https://github.com/llnl/H5Z-ZFP/issues/159
repo_url: https://github.com/llnl/H5Z-ZFP
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/llnl/H5Z-ZFP/issues/159' target='_blank'>llnl/H5Z-ZFP#159</a>.

<small>> I see. So let me sure I get this right. The use case we're discussing is when an application like Matlab knows nothing about zfp or H5Z-ZFP (e.g., it has not been linked against those libraries), but instead relies on the HDF5 library to invoke zfp. This is done by having the application/user set the filter number (32013) and enough `cd_values` to specify zfp compression mode and parameters. The HDF5 library will then, when encountering the filter number, dynamically load the H5Z-ZFP and zfp libraries, which will encode additional `cd_values` (the zfp header) and then compress the data. Did I get that right?...</small>

<a href='https://github.com/llnl/H5Z-ZFP/issues/159' target='_blank'>View Comment</a>