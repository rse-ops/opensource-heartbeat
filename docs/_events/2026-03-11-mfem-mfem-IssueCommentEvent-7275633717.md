---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2026-03-11
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/5260
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/mfem/mfem/issues/5260' target='_blank'>mfem/mfem#5260</a>.

<small>Hi Nuno, thank you for your investigation into this issue. We have the miniapp `mfem/miniapps/meshing/phpref.cpp` which simply demonstrates the capability of h- and p-refinement in parallel, with random selection of refinements and no use of estimators. As far as I know, estimators have not been developed for use in hp-refinement. The limitations you described for estimators after p-refinement make sense to me, and I agree that more work is needed. I think it would be a useful contribution	if you would like to work on this, and I don't think it would conflict with any existing work. Starting with H1/L2 should be sufficient....</small>

<a href='https://github.com/mfem/mfem/issues/5260' target='_blank'>View Comment</a>