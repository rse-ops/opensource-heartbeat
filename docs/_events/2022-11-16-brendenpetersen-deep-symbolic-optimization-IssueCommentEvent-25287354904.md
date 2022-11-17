---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/15270620?"
user: brendenpetersen
date: 2022-11-16
repo_name: brendenpetersen/deep-symbolic-optimization
html_url: https://github.com/brendenpetersen/deep-symbolic-optimization/issues/49
repo_url: https://github.com/brendenpetersen/deep-symbolic-optimization
---

<a href='https://github.com/brendenpetersen' target='_blank'>brendenpetersen</a> commented on issue <a href='https://github.com/brendenpetersen/deep-symbolic-optimization/issues/49' target='_blank'>brendenpetersen/deep-symbolic-optimization#49</a>.

<small>Hi, unfortunately our `multiobject` parts of the code are not very well tested because it's a pretty narrow use case for us. I think the issue is over in `program.py::Program.__getstate__` and `program.py::Program.__setstate__`. These define how `multiprocessing` passes `Program` objects back and forth, and apparently this was not done correctly for the `multiobject=True` case....</small>

<a href='https://github.com/brendenpetersen/deep-symbolic-optimization/issues/49' target='_blank'>View Comment</a>