---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-08-12
repo_name: EnzymeAD/Enzyme
html_url: https://github.com/EnzymeAD/Enzyme/issues/1375
repo_url: https://github.com/EnzymeAD/Enzyme
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/EnzymeAD/Enzyme/issues/1375' target='_blank'>EnzymeAD/Enzyme#1375</a>.

<small>@wsmoses  We could use a macro that expands to this attribute, but the question is where to put it. If the answer is "everywhere except certain numerical routines", we'd probably just put the attribute into `PETSC_EXTERN` (assuming the attribute can be used at the declaration site and not repeated at the definition (e.g., like visibility attributes), making a new `PETSC_EXTERN_ACTIVE` (or something more precise) for those functions that are active....</small>

<a href='https://github.com/EnzymeAD/Enzyme/issues/1375' target='_blank'>View Comment</a>