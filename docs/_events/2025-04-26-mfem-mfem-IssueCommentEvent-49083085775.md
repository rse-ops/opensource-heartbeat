---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2025-04-26
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/4831
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/issues/4831' target='_blank'>mfem/mfem#4831</a>.

<small>I don't think the H(curl) case is supported yet. Probably the first step is to add element assembly (EA) support in `VectorFEMassIntegrator::AssembleEA`. Full assembly (FA) is based on EA and may just work when EA is supported, however, there may be some other pieces missing -- I'm not 100% sure....</small>

<a href='https://github.com/mfem/mfem/issues/4831' target='_blank'>View Comment</a>