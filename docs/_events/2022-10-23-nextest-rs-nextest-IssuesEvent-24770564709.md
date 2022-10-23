---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-10-23
repo_name: nextest-rs/nextest
html_url: https://github.com/nextest-rs/nextest/issues/605
repo_url: https://github.com/nextest-rs/nextest
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> open issue <a href='https://github.com/nextest-rs/nextest/issues/605' target='_blank'>nextest-rs/nextest#605</a>.

<p>Run parallel tests under MPI</p><small>In scientific computing, it's common to have tests that must run with multiple processes (that communicate with each other), often using MPI. In [rsmpi](https://github.com/rsmpi/rsmpi/), we have a bunch of separate executables and a clumsy [bash script](https://github.com/rsmpi/rsmpi/blob/main/ci/run-examples.sh) that uses [`cargo-mpirun`](https://github.com/AndrewGaspar/cargo-mpirun/blob/master/src/mpirun.rs) to execute those. This is slow and has poor usability. Some of us are working on more Rust libraries that use MPI, so this need will continue to grow and nextest support would be a huge enabler....</small><a href='https://github.com/nextest-rs/nextest/issues/605' target='_blank'>View Comment</a>