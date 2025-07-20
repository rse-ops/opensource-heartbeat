---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2025-07-18
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/4326
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/mfem/mfem/pull/4326' target='_blank'>mfem/mfem#4326</a>.

<small>Thanks @IdoAkkerman for your updates. I verified that the results for the `nurbs_surface` are unchanged in the eyeball norm, with differences on the order of round-off, due to the different choice of points used by `GetInterpolant`. My understanding is that `GetInterpolant` generalizes `FindInterpolant`, with `Demko` points usually being preferable. The changes in this PR seem good to me, to deprecate `FindInterpolant` in favor of `GetInterpolant`....</small>

<a href='https://github.com/mfem/mfem/pull/4326' target='_blank'>View Comment</a>