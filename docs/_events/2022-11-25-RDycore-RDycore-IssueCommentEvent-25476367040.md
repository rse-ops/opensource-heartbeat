---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-11-25
repo_name: RDycore/RDycore
html_url: https://github.com/RDycore/RDycore/issues/8
repo_url: https://github.com/RDycore/RDycore
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/RDycore/RDycore/issues/8' target='_blank'>RDycore/RDycore#8</a>.

<small>Are we planning to use slope reconstruction? I assume yes (but maybe not immediately). For ex11 (which was moved into `PetscFV`), we computed pseudoinverses and placed into face-based storage so slope reconstruction was still a face traversal. Once the cell-centered slopes have been computed, there is another face traversal reconstructing left and right face values and solving Riemann problems. I think to the extent we build matrices for implicit solvers, it would be for the `zero` slope reconstruction, which produces a much sparser matrix and ensures h-ellipticity (and computationally, you skip the first pass)....</small>

<a href='https://github.com/RDycore/RDycore/issues/8' target='_blank'>View Comment</a>