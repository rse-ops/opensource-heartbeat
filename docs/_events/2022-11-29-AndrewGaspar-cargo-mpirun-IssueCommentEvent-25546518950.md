---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-11-29
repo_name: AndrewGaspar/cargo-mpirun
html_url: https://github.com/AndrewGaspar/cargo-mpirun/issues/8
repo_url: https://github.com/AndrewGaspar/cargo-mpirun
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/AndrewGaspar/cargo-mpirun/issues/8' target='_blank'>AndrewGaspar/cargo-mpirun#8</a>.

<small>`cargo-mpirun` is currently hard-coded to use `mpiexec`, which might not be appropriate on your cluster. In that case, you need to `cargo build --bin my-app` your executable and then use `srun -n 4 target/release/my-app` or whatever launcher your cluster uses....</small>

<a href='https://github.com/AndrewGaspar/cargo-mpirun/issues/8' target='_blank'>View Comment</a>