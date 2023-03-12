---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/14316120?"
user: bwpriest
date: 2023-03-10
repo_name: LLNL/MuyGPyS
html_url: https://github.com/LLNL/MuyGPyS/issues/96
repo_url: https://github.com/LLNL/MuyGPyS
---

<a href='https://github.com/bwpriest' target='_blank'>bwpriest</a> open issue <a href='https://github.com/LLNL/MuyGPyS/issues/96' target='_blank'>LLNL/MuyGPyS#96</a>.

<p>Need torch MuyGPyS layer to support 64 bit optimization</p><small>We currently need to use `$ export MUYGPYS_FTYPE=32` for `MuyGPyS.torch.muygpys_layer` to perform correctly during optimization. This is because `.float()` is hardcoded therein. We need to modify this behavior so that it depends on `mm.ftype`. ...</small><a href='https://github.com/LLNL/MuyGPyS/issues/96' target='_blank'>View Comment</a>