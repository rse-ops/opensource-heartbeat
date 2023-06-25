---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-06-24
repo_name: FreeCAD/FreeCAD
html_url: https://github.com/FreeCAD/FreeCAD/pull/9766
repo_url: https://github.com/FreeCAD/FreeCAD
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/FreeCAD/FreeCAD/pull/9766' target='_blank'>FreeCAD/FreeCAD#9766</a>.

<small>Regarding using the Python interface to Gmsh, I think there is benefit to separate processes because I've sometimes crashed gmsh and you don't want that to also crash the freecad process. Meshing can be very expensive and you'd rather it not lock up the interface and that you can break it if it's taking too much time or memory. So you could use a subprocess to call Gmsh's Python interface, but I'm not sure how much benefit that has and it's nice to be able to drive Gmsh directly sometimes. (We can take this conversation elsewhere if it needs anything more.)...</small>

<a href='https://github.com/FreeCAD/FreeCAD/pull/9766' target='_blank'>View Comment</a>