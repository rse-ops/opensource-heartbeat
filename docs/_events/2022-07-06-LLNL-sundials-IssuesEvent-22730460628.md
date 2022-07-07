---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/5669480?"
user: balos1
date: 2022-07-06
repo_name: LLNL/sundials
html_url: https://github.com/LLNL/sundials/issues/158
repo_url: https://github.com/LLNL/sundials
---

<a href='https://github.com/balos1' target='_blank'>balos1</a> closed issue <a href='https://github.com/LLNL/sundials/issues/158' target='_blank'>LLNL/sundials#158</a>.

<p>Lapack Band vs KLU solver</p><small>Hello, with a simple benchmark on the heat equation in a cube with finite differences, I noticed (under macOS/Intel) that with a 30x30x30 discretisation cvode is 3 times faster with the Lapack/band solver (with [n^2,n^2] bandwitdth and DQ jacobian than with KLU and exact sparse Jacobian. When looking at the cpu history I can see that the LapackBand solver uses all cores (likely during elimination and back substitution phase of linear solves), which is expected since Lapack on macOS uses Altivec instruction set. When using the KLU linear solver, only one core is used. Hence, I suppose that I should got for SuperLU_MT solver instead ?...</small><a href='https://github.com/LLNL/sundials/issues/158' target='_blank'>View Comment</a>