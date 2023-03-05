---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/14316120?"
user: bwpriest
date: 2023-03-01
repo_name: LLNL/MuyGPyS
html_url: https://github.com/LLNL/MuyGPyS/issues/94
repo_url: https://github.com/LLNL/MuyGPyS
---

<a href='https://github.com/bwpriest' target='_blank'>bwpriest</a> open issue <a href='https://github.com/LLNL/MuyGPyS/issues/94' target='_blank'>LLNL/MuyGPyS#94</a>.

<p>library needs to be more functional</p><small>I have come to the conclusion that MuyGPyS has too many procedural conditionals to be maintainable. We need to refactor much of the library to functionally construct MuyGPs processes in a way that is set at object creation time. In particular, we need to break `MuyGPS.regress` into `MuyGPS.posterior_mean()` and `MuyGPS.posterior_variance()`. Rather than writing these methods as normal member functions, they should be defined at object creation time based upon model choices - e.g. homo/heterscedasticity, variance form, etc. There are other examples that I will document in this thread as they arise....</small><a href='https://github.com/LLNL/MuyGPyS/issues/94' target='_blank'>View Comment</a>