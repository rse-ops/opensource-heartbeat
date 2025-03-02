---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2025-03-01
repo_name: coreylowman/cudarc
html_url: https://github.com/coreylowman/cudarc/issues/340
repo_url: https://github.com/coreylowman/cudarc
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> open issue <a href='https://github.com/coreylowman/cudarc/issues/340' target='_blank'>coreylowman/cudarc#340</a>.

<p>soundness with async copies</p><small>The non-`sync` copy interfaces do not hold onto the host memory, so subsequent modification of the host memory can race with the DMA transfer to device. This is an example with `htod_copy_pinned` #336. Small sizes will spuriously pass this test due to what looks like eager copying, but N=10000 here fails every time in my tests (cuda-12.8, sm_89)....</small><a href='https://github.com/coreylowman/cudarc/issues/340' target='_blank'>View Comment</a>