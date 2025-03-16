---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2025-03-14
repo_name: CEED/libCEED
html_url: https://github.com/CEED/libCEED/issues/1775
repo_url: https://github.com/CEED/libCEED
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/CEED/libCEED/issues/1775' target='_blank'>CEED/libCEED#1775</a>.

<small>I see you edited the comment. Centroid and moment of inertia are integral quantities you could compute and compare to reference values. Those have no iteration or "solver" needed. Solving even a simple problem requires a "solver" (which for sufficiently small problems could be unpreconditioned CG, otherwise you need at least a preconditioner). Usually we use PETSc for anything that needs a solver, so that we don't replicate such functionality in libCEED (we regard most such things as being out of scope for the library)....</small>

<a href='https://github.com/CEED/libCEED/issues/1775' target='_blank'>View Comment</a>