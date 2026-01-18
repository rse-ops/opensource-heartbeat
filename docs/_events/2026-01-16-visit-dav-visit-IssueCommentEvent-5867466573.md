---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2026-01-16
repo_name: visit-dav/visit
html_url: https://github.com/visit-dav/visit/pull/20752
repo_url: https://github.com/visit-dav/visit
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/visit-dav/visit/pull/20752' target='_blank'>visit-dav/visit#20752</a>.

<small>Ok, so both the HDF5 and Silo build failures are fixed by specifing `-DMPI_HOME:STRING=/path/to/mpi/install/home`. Now, Silo of course DOES NOT REQUIRE mpi. But, it does a `find_package()` on HDF5 and that will fail if the HDF5 it is finding depends on MPI but there is nothing telling Silo where to find MPI....</small>

<a href='https://github.com/visit-dav/visit/pull/20752' target='_blank'>View Comment</a>