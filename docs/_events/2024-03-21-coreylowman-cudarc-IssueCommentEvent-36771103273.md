---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2024-03-21
repo_name: coreylowman/cudarc
html_url: https://github.com/coreylowman/cudarc/issues/196
repo_url: https://github.com/coreylowman/cudarc
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/coreylowman/cudarc/issues/196' target='_blank'>coreylowman/cudarc#196</a>.

<small>It's quite common in the HPC world that interactive nodes do not have GPUs nor the drivers, but the compute nodes do. This is fine when just using `libcudart.so` because it loads the driver dynamically, and one can use `$CUDA_DIR/lib/stubs/` if your code calls the driver interface directly. I think similar/better usability is desirable for Rust, especially if it means we can distribute a static binary that can run on CPU machines without any CUDA libraries or devices, but can use devices when selected by run-time options on a machine that has them....</small>

<a href='https://github.com/coreylowman/cudarc/issues/196' target='_blank'>View Comment</a>