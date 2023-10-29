---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-10-27
repo_name: RDycore/RDycore
html_url: https://github.com/RDycore/RDycore/issues/102
repo_url: https://github.com/RDycore/RDycore
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/RDycore/RDycore/issues/102' target='_blank'>RDycore/RDycore#102</a>.

<small>We could look to ceed-fluids and ratel for an example (we use `-continue_filename checkpoint.bin`, as a PETSc binary file with metadata before the solution state). It does not support changing the number of processes -- we intend to support that with CGNS, but it requires a mesh file (not generating on the fly) since you need to know how to interpret the solution checkpoint. With CGNS, those are already connected. We'll be implementing this in PETSc so it'll just be available. I would not recommend writing scatters directly in rdycore....</small>

<a href='https://github.com/RDycore/RDycore/issues/102' target='_blank'>View Comment</a>