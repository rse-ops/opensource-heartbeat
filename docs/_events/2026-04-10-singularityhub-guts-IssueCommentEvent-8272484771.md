---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2026-04-10
repo_name: singularityhub/guts
html_url: https://github.com/singularityhub/guts/issues/10
repo_url: https://github.com/singularityhub/guts
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/singularityhub/guts/issues/10' target='_blank'>singularityhub/guts#10</a>.

<small>We would need a `SingularityContainer` class akin to the [DockerContainer](https://github.com/singularityhub/guts/blob/main/container_guts/main/container/docker.py) class that exposes the same function signatures, and I think that would do it. Knowing Singularity images, the issue we might run into is with respect to speed to do the same operations, but it is worth a test! If you are interested in taking a shot, the main entrypoint creates a `ManifestGenerator` that is going to call extract on that class. That happens here:...</small>

<a href='https://github.com/singularityhub/guts/issues/10' target='_blank'>View Comment</a>