---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/2072964?"
user: BradWhitlock
date: 2026-02-06
repo_name: llnl/axom
html_url: https://github.com/llnl/axom/issues/1713
repo_url: https://github.com/llnl/axom
---

<a href='https://github.com/BradWhitlock' target='_blank'>BradWhitlock</a> closed issue <a href='https://github.com/llnl/axom/issues/1713' target='_blank'>llnl/axom#1713</a>.

<p>Polygon clipping in primal is prone to making bad vertices in some cases.</p><small>I ran across some Polygon clipping problems in primal when looking at some 2D `ElviraAlgorithm` output. The output polygons contained an invalid (0,0) vertex well outside the input shape. That's BAD. I was able to work around this to some degree by passing smaller tolerances to `axom::primal::clip()` for the Polygon case. For some other polygons, tolerances did not help....</small><a href='https://github.com/llnl/axom/issues/1713' target='_blank'>View Comment</a>