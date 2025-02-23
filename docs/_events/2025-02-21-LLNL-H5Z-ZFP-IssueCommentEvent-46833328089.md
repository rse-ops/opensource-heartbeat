---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2025-02-21
repo_name: LLNL/H5Z-ZFP
html_url: https://github.com/LLNL/H5Z-ZFP/pull/153
repo_url: https://github.com/LLNL/H5Z-ZFP
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/LLNL/H5Z-ZFP/pull/153' target='_blank'>LLNL/H5Z-ZFP#153</a>.

<small>> Actually, let me make one more point about inner vs. outer dimensions. It would be possible to always use _x_, _y_, ... as the domain dimensions, even when the fastest varying dimensions are part of the range. This is because zfp supports strided layouts, where the leftmost dimension does not necessarily vary fastest. So instead of a default stride of 1 for _x_ and 4 for _y_ in the tensor field example above, you could set them to 6 and 24, respectively, with the strides for _z_ and _w_ set to 1 and 2. There would possibly be a performance penalty, however, as zfp loops over _x_ in the innermost loop, and the data would be gathered and scattered non-contiguously....</small>

<a href='https://github.com/LLNL/H5Z-ZFP/pull/153' target='_blank'>View Comment</a>