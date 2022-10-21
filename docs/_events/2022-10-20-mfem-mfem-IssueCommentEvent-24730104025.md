---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5412886?"
user: jandrej
date: 2022-10-20
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/issues/3219
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/jandrej' target='_blank'>jandrej</a> commented on issue <a href='https://github.com/mfem/mfem/issues/3219' target='_blank'>mfem/mfem#3219</a>.

<small>@logantm2 excuse the late response. Let's say you want to apply an operator $$F^e U_h^e = \hat{U}_h^e.$$ In this case it doesn't matter if the space is H1 or L2 (I'm not sure about vector FE spaces) because we can operate on the E-vector level in both cases. For the approach below you will need to define a matrix that "weighs" the modes you want to keep. E.g. if you want remove all high order modes, you define `D_filter` as a diagonal matrix, with ones on the diagonal for modes that you want to keep and zeros otherwise. Then evaluate your desired polynomials at the quadrature points (here I'm using a Tensor basis and only evaluate the polynomials for 1D)....</small>

<a href='https://github.com/mfem/mfem/issues/3219' target='_blank'>View Comment</a>