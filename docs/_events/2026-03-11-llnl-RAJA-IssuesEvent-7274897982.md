---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/2072964?"
user: BradWhitlock
date: 2026-03-11
repo_name: llnl/RAJA
html_url: https://github.com/llnl/RAJA/issues/2004
repo_url: https://github.com/llnl/RAJA
---

<a href='https://github.com/BradWhitlock' target='_blank'>BradWhitlock</a> open issue <a href='https://github.com/llnl/RAJA/issues/2004' target='_blank'>llnl/RAJA#2004</a>.

<p>Exclusive_scan makes wrong answer for char to int output on HIP.</p><small>I have places in my code where I do an `exclusive_scan()` over a mask and make some offsets from it. I wanted to experiment with making my masks `char` while leaving the scan output as `int` or `long`. I wanted the scan to accumulate using the output type so I passed `RAJA::operators::plus<T_out>{}` as an argument to the scan. That is enough to make it work for SEQ, OMP, and CUDA. With HIP it does not work and makes some negative offsets once char overflows....</small><a href='https://github.com/llnl/RAJA/issues/2004' target='_blank'>View Comment</a>