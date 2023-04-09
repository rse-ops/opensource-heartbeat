---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/7818666?"
user: hppritcha
date: 2023-04-08
repo_name: open-mpi/ompi
html_url: https://github.com/open-mpi/ompi/issues/11407
repo_url: https://github.com/open-mpi/ompi
---

<a href='https://github.com/hppritcha' target='_blank'>hppritcha</a> closed issue <a href='https://github.com/open-mpi/ompi/issues/11407' target='_blank'>open-mpi/ompi#11407</a>.

<p>MPI-4: Session error handler function not called</p><small>I'm working on implementing `Create_errhandler()` methods in mpi4py. I've always procrastinate to do it because a) no one ever asked, and b) creating error handlers with the C bindings is definitely not friendly for dynamic languages like Python, so a compromise have to be made (e.g. limiting the number of error handlers that can be ever created). However, after mpi4py/mpi4py#307 from @bosilca to support ULFM and realizing that many ULFM tests/examples/tutorials do use custom error handlers, I decided to move forward in mpi4py/mpi4py#310. As usual, I've added some lightweight testing, but one of my tests failed when using `Session`, but `Comm`/`Win`/`File` are OK....</small><a href='https://github.com/open-mpi/ompi/issues/11407' target='_blank'>View Comment</a>