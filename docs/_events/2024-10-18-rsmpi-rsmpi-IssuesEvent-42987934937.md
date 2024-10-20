---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2024-10-18
repo_name: rsmpi/rsmpi
html_url: https://github.com/rsmpi/rsmpi/issues/189
repo_url: https://github.com/rsmpi/rsmpi
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> closed issue <a href='https://github.com/rsmpi/rsmpi/issues/189' target='_blank'>rsmpi/rsmpi#189</a>.

<p>Derive implementation of `Equivalence` hard codes `mpi` path</p><small>The `Equivalence` derive macro expects `mpi` to be an explicit dependency of the crate using the derive macro by hard coding the `mpi` dependency in the paths of the types used in the proc macro, e.g. `::mpi::some::field`. An error is returned if `mpi` is provided some other way, e.g. as a re-export in a dependency....</small><a href='https://github.com/rsmpi/rsmpi/issues/189' target='_blank'>View Comment</a>