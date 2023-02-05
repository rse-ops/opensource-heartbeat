---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/2072964?"
user: BradWhitlock
date: 2023-01-30
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/1073
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/BradWhitlock' target='_blank'>BradWhitlock</a> open issue <a href='https://github.com/LLNL/conduit/issues/1073' target='_blank'>LLNL/conduit#1073</a>.

<p>Evaluate face node ordering in TOPO_WEDGE_EMBEDDING, TOPO_PYRAMID_EMBEDDING.</p><small>The face node ordering in TOPO_*_EMBEDDING shapes is counter-clockwise when viewed from the outside of the element for TET and HEX elements. The pyramid and wedge (wedge especially) contains some triangles that are clockwise from the outside of the element - using a VTK node ordering. It seems they should be consistent (all counter-clockwise) but this will change the element edge ordering, if that matters....</small><a href='https://github.com/LLNL/conduit/issues/1073' target='_blank'>View Comment</a>