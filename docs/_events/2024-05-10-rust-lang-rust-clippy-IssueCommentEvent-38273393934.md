---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2024-05-10
repo_name: rust-lang/rust-clippy
html_url: https://github.com/rust-lang/rust-clippy/issues/6816
repo_url: https://github.com/rust-lang/rust-clippy
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/rust-lang/rust-clippy/issues/6816' target='_blank'>rust-lang/rust-clippy#6816</a>.

<small>A backward-stable algorithm evaluating a function $f$ with condition number $\kappa$ has a relative error bounded by $\kappa \, \epsilon_{\text{machine}}$. In many cases for which $f(x) = 0$, the condition number blows up. For example, the algorithm `|x| (1.0 + x) - 1.0` is unstable because its second operation has unbounded condition number as $x\to 0$, and indeed produces relative error of size 1. We can't give reliable advice for a (relative or absolute) tolerance without knowing the condition numbers involved. In the above example, the condition number of the entire function is 1 (great!) but the algorithm is unstable and thus violates any useful relative error bound. It would be nice if users always wrote backward-stable algorithms, but it's going to be really confusing if the lint is telling people to test with a tolerance that can only be achieved with by doing so. When the functions are differentiable, we could estimate a condition number and provide diagnostics about numerical stability using Enzyme (cf. https://github.com/rust-lang/rust/issues/124509)....</small>

<a href='https://github.com/rust-lang/rust-clippy/issues/6816' target='_blank'>View Comment</a>