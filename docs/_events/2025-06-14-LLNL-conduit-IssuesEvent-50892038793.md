---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/2072964?"
user: BradWhitlock
date: 2025-06-14
repo_name: LLNL/conduit
html_url: https://github.com/LLNL/conduit/issues/1444
repo_url: https://github.com/LLNL/conduit
---

<a href='https://github.com/BradWhitlock' target='_blank'>BradWhitlock</a> open issue <a href='https://github.com/LLNL/conduit/issues/1444' target='_blank'>LLNL/conduit#1444</a>.

<p>Partitioner fails when multiple topologies provide adjsets.</p><small>I wrote a new test case to test adjset spatial sorting, which makes a mesh and generates lines and corners for it and validates the adjsets. Later, I decided to hook up partitioning. I made the partitioned mesh after the other meshes. It caused the partitioner to crash because topologies _(other than the one being partitioned)_ had adjsets already defined. The [logic loops over all adjsets](https://github.com/LLNL/conduit/blob/554373f4bd4ffdfbd5bb9c43ac6152ed4c856f57/src/libs/blueprint/conduit_blueprint_mesh_partition.cpp#L4183) in the domain, which is not right....</small><a href='https://github.com/LLNL/conduit/issues/1444' target='_blank'>View Comment</a>