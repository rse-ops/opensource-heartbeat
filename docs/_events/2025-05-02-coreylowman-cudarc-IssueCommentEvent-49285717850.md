---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2025-05-02
repo_name: coreylowman/cudarc
html_url: https://github.com/coreylowman/cudarc/issues/401
repo_url: https://github.com/coreylowman/cudarc
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/coreylowman/cudarc/issues/401' target='_blank'>coreylowman/cudarc#401</a>.

<small>I think the weakest answer to these depends on the implementation language doing the copy or handling results on the device. But suppose the kernel that'll operate on the device data was written in Rust? In that case, the uninitialized memory cannot exist in a slice or similar object (it must be behind `MaybeUnint<T>` or a raw pointer). I think it's preferable for cudarc to enforce that slice-like objects on host or device contain only initialized memory. (One can use `MaybeUninit<T>` if they really need to handle uninitialized memory.)...</small>

<a href='https://github.com/coreylowman/cudarc/issues/401' target='_blank'>View Comment</a>