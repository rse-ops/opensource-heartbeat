---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2022-09-09
repo_name: rsmpi/rsmpi
html_url: https://github.com/rsmpi/rsmpi/issues/133
repo_url: https://github.com/rsmpi/rsmpi
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/rsmpi/rsmpi/issues/133' target='_blank'>rsmpi/rsmpi#133</a>.

<small>Indeed, this is a safety concern. FWIW, it is valid to receive into a buffer that's "too long". This is used frequently for irregular data. You get the status and inquire using `MPI_Get_count`. We use this in a few dozen places in PETSc, for example. (Those could likely be consolidated, but the point is that it's not super fringe usage.)...</small>

<a href='https://github.com/rsmpi/rsmpi/issues/133' target='_blank'>View Comment</a>