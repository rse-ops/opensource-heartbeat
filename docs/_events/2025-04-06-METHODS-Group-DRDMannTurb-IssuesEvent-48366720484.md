---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/74629347?"
user: alizma
date: 2025-04-06
repo_name: METHODS-Group/DRDMannTurb
html_url: https://github.com/METHODS-Group/DRDMannTurb/issues/160
repo_url: https://github.com/METHODS-Group/DRDMannTurb
---

<a href='https://github.com/alizma' target='_blank'>alizma</a> open issue <a href='https://github.com/METHODS-Group/DRDMannTurb/issues/160' target='_blank'>METHODS-Group/DRDMannTurb#160</a>.

<p>Benchmarking speed and GPU use as a regression test</p><small>The current test suite for the package has some basic test that just checks PyTorch's observed _GPU utilization_ when an NN is being trained and ensuring that the percentage is high. The intention was to automatically detect if new features to the core of the package were introducing CPU-GPU device communication and/or messing with data layouts. But the way this test currently works isn't all that useful since only the most basic configuration is checked while many use-cases where incorrect data-loading might reduce performance are just not treated, and moreover, GPU utilization is a [misleading metric](https://www.trainy.ai/blog/gpu-utilization-misleading). Basing a test on MFU, as discussed in that post, would not only be more useful for benchmarking the code's speed and resource use, but also serve as a better regression test. ...</small><a href='https://github.com/METHODS-Group/DRDMannTurb/issues/160' target='_blank'>View Comment</a>