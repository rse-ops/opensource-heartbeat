---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/2072964?"
user: BradWhitlock
date: 2025-04-23
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/1429
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/BradWhitlock' target='_blank'>BradWhitlock</a> open issue <a href='https://github.com/LLNL/conduit/issues/1429' target='_blank'>LLNL/conduit#1429</a>.

<p>generate_corners() does not work for "mixed" unstructured topology.</p><small>``generate_corners()`` uses the ShapeType and ShapeCascade classes to help figure out how to decompose the mesh into faces/edges/points. When you give "mixed" to ShapeType, it initializes with -1 for dims and other fields. This crashes later on in ShapeCascade when attempting to use dims as an array index, ultimately leading to a seg fault....</small><a href='https://github.com/LLNL/conduit/issues/1429' target='_blank'>View Comment</a>