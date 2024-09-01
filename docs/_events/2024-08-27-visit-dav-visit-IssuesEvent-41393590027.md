---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/2072964?"
user: BradWhitlock
date: 2024-08-27
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/issues/19780
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/BradWhitlock' target='_blank'>BradWhitlock</a> closed issue <a href='https://github.com/visit-dav/visit/issues/19780' target='_blank'>visit-dav/visit#19780</a>.

<p>Blueprint reader not using offsets for unstructured topologies.</p><small>I had a mesh where I left some extra unused slots in the elements/connectivity array. I turned some quads into triangles. The elements/sizes were set to the right length and the elements/offsets were valid for seeking to each element. VisIt did not plot this correctly since the Blueprint code was not using elements/offsets to seek through the zones in the mesh (it was using sizes)....</small><a href='https://github.com/visit-dav/visit/issues/19780' target='_blank'>View Comment</a>