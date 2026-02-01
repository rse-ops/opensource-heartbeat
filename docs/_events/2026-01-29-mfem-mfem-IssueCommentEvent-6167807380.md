---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12926030?"
user: v-dobrev
date: 2026-01-29
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/5210
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/v-dobrev' target='_blank'>v-dobrev</a> commented on issue <a href='https://github.com/mfem/mfem/pull/5210' target='_blank'>mfem/mfem#5210</a>.

<small>I thought about this issue and I think a better solution is to `= delete` the move-assignment operator of `DenseMatrix`. This way assignments to `DenseMatrix` will always be copy-assignments. The reason I think this is a better solution is that re-defining the move-assignment (especially at the level of `Array`) to do a deep copy, in the case when the LHS is an alias, goes against the idea of move-assignment. We will lose the ability to move-assign `DenseMatrix` but that is not a big deal, I think -- this was already the case for a long time before we added it in #4028....</small>

<a href='https://github.com/mfem/mfem/pull/5210' target='_blank'>View Comment</a>