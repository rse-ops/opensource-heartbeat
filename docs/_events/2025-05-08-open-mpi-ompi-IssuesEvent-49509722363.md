---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/7818666?"
user: hppritcha
date: 2025-05-08
repo_name: open-mpi/ompi
html_url: https://github.com/open-mpi/ompi/issues/13242
repo_url: https://github.com/open-mpi/ompi
---

<a href='https://github.com/hppritcha' target='_blank'>hppritcha</a> open issue <a href='https://github.com/open-mpi/ompi/issues/13242' target='_blank'>open-mpi/ompi#13242</a>.

<p>bindings: python check in configury needs to be improved</p><small>There's a check in ```ompi_configure_options.m4``` for python 3.6 or higher to support generation of the top level c and fortran f08 bindings from the code in ompi/mpi/bindings.  That's fine, but the file being used as a sentinel to tell whether or not the bindings have already been generated is not correct.  the names of the generated files has changed and ompi_send.c is not being generated, rather a differently named file.  ...</small><a href='https://github.com/open-mpi/ompi/issues/13242' target='_blank'>View Comment</a>