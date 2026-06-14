---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/5669480?"
user: balos1
date: 2026-06-10
repo_name: llnl/sundials
html_url: https://github.com/llnl/sundials/issues/955
repo_url: https://github.com/llnl/sundials
---

<a href='https://github.com/balos1' target='_blank'>balos1</a> open issue <a href='https://github.com/llnl/sundials/issues/955' target='_blank'>llnl/sundials#955</a>.

<p>[BUG] arkLsMassSolve ignores some return values from user callbacks.</p><small>One of the folks working on the deal.II SUNDIALS interfaces, @vovannikov, has spent what I think must have been a quality afternoon tracing why one of our tests fails. The details are in https://github.com/dealii/dealii/pull/19838 but come down to code that I (mis-)wrote: If a user callback fails in user-provided linear solvers, I either returned +1 or -1, depending on whether it's a recoverable or non-recoverable failure (and zero if everything is fine). I *think* that's what the documentation of SUNDIALS at some point said I should do, but it's possible that that was about the nonlinear solver callbacks in KINSOL and not about the SUNDIALS linear solvers. Regardless, for the linear solvers, I need to return `SUNLS_PSOLVE_FAIL_REC` or `SUNLS_PSOLVE_FAIL_UNREC`, with values +805 and -808, respectively....</small><a href='https://github.com/llnl/sundials/issues/955' target='_blank'>View Comment</a>