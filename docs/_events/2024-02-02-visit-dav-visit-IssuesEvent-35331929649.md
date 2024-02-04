---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/35237779?"
user: JustinPrivitera
date: 2024-02-02
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/18716
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/JustinPrivitera' target='_blank'>JustinPrivitera</a> closed issue <a href='https://github.com/visit-dav/visit/issues/18716' target='_blank'>visit-dav/visit#18716</a>.

<p>Blueprint Reader: Unstructured Points case is not correctly handled</p><small>Blueprint allows two kinds of point meshes. One is implicit: you set up explicit coordinates and then define an [implicit topology](https://llnl-conduit.readthedocs.io/en/latest/blueprint_mesh.html#implicit-topology) of points on top of it. The topology will use all the points in the coordinate set. The other kind of point mesh is an unstructured mesh where the shape type is points. The difference is illustrated by the `braid` [example](https://llnl-conduit.readthedocs.io/en/latest/blueprint_mesh.html#braid). You can choose to have an explicit coordset with an explicit topo of points or an explicit coordset with an implicit topo of points. The unstructured (explicit) points case allows us to specify which points from the coordinate set we want to use....</small><a href='https://github.com/visit-dav/visit/issues/18716' target='_blank'>View Comment</a>