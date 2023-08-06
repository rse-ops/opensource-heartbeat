---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-08-04
repo_name: SCOREC/core
html_url: https://github.com/SCOREC/core/pull/395
repo_url: https://github.com/SCOREC/core
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/SCOREC/core/pull/395' target='_blank'>SCOREC/core#395</a>.

<small>I'm not sure if I'm reading your whole post correctly, but this is how we do it in PETSc. Each rank creates a connectivity array for the elements it owns, and the collective write is done in these two lines (the first is metadata, the second is array data). https://gitlab.com/petsc/petsc/-/blob/main/src/dm/impls/plex/cgns/plexcgns2.c?ref_type=heads#L791-792...</small>

<a href='https://github.com/SCOREC/core/pull/395' target='_blank'>View Comment</a>