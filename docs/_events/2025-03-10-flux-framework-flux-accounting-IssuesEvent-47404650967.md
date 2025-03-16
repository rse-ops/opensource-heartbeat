---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/20131404?"
user: cmoussa1
date: 2025-03-10
repo_name: flux-framework/flux-accounting
html_url: https://github.com/flux-framework/flux-accounting/issues/593
repo_url: https://github.com/flux-framework/flux-accounting
---

<a href='https://github.com/cmoussa1' target='_blank'>cmoussa1</a> open issue <a href='https://github.com/flux-framework/flux-accounting/issues/593' target='_blank'>flux-framework/flux-accounting#593</a>.

<p>`update-usage`: past usage factors not actually getting applied, not going all the way back to last usage period</p><small>While doing some random experimentation on `fluke`, I noticed that the past usage period job usage factors for associations was not actually getting updated. Only the most current period was being calculated. I think this is because the `apply_decay_factor()` function was not actually committing any of the `UPDATE` statements it was executing. I need to add a `.commit()` to the end of the `UPDATE`s....</small><a href='https://github.com/flux-framework/flux-accounting/issues/593' target='_blank'>View Comment</a>