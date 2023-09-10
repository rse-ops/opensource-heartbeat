---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-09-08
repo_name: CEED/libCEED
html_url: https://github.com/CEED/libCEED/issues/1328
repo_url: https://github.com/CEED/libCEED
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/CEED/libCEED/issues/1328' target='_blank'>CEED/libCEED#1328</a>.

<small>I don't know what is meant by "mesh quadrature space", but the particle operators will all have the form $E_o^T B_o^T D B_i E_i$ where one of the input or output bases can be an identity (so the results are collocated at particles), otherwise the inputs/outputs are FE fields. Everything involving particles is separate from Gauss quadrature points (must move though standard FE fields to go between particles and quadrature). SNES residual will have both $B_i$ and $B_o$ acting on FE fields. In particular, $B_i$ will compute a gradient of displacement (so strain can be defined at particles) and $B_o$ will be interpolation of a constitutive model output. Given that nodal field, there will be a standard FE L^2 projection or differential filter (still close to a mass matrix) and likely another standard field qfunction -- both of these have no reference to particles....</small>

<a href='https://github.com/CEED/libCEED/issues/1328' target='_blank'>View Comment</a>