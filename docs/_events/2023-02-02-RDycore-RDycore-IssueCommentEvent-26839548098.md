---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-02-02
repo_name: RDycore/RDycore
html_url: https://github.com/RDycore/RDycore/issues/13
repo_url: https://github.com/RDycore/RDycore
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/RDycore/RDycore/issues/13' target='_blank'>RDycore/RDycore#13</a>.

<small>Sort of. Xdmf is an XML header that can access arrays living in an HDF5 file. The XML makes it so tools like Paraview can interpret it. But the Xdmf working group is pretty defunct and it seems like an abandoned effort. The `.h5` format that Vaclav and Matt use has some parts that are not representable as Xdmf and I don't think you'll get meshio to write something that their parallel reader can use directly. I'd suggest letting meshio export as Gmsh format -- that'll take us a long way and we can revisit when we're running huge meshes....</small>

<a href='https://github.com/RDycore/RDycore/issues/13' target='_blank'>View Comment</a>