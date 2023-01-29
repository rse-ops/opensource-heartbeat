---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/2072964?"
user: BradWhitlock
date: 2023-01-28
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/1070
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/BradWhitlock' target='_blank'>BradWhitlock</a> open issue <a href='https://github.com/LLNL/conduit/issues/1070' target='_blank'>LLNL/conduit#1070</a>.

<p>The unstructured::generate_offsets function changes the offset types for polyhedral meshes if offsets already exist.</p><small>We had a polyhedral mesh that already had integer elements/offsets in its topology. This topology was unconditionally passed through generate_offsets() in blueprint to generate the offsets if they did not already exist. After the call, the elements/offsets were int64 and this caused some other code that assumed int32 to crash in a node.as_int32_ptr() call....</small><a href='https://github.com/LLNL/conduit/issues/1070' target='_blank'>View Comment</a>