---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2026-01-25
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/5203
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/mfem/mfem/pull/5203' target='_blank'>mfem/mfem#5203</a>.

<small>What is the policy for output in unit tests? There is `std::cout << std::flush;` in `fem/test_var_order.cpp` and other calls to `cout` `if (verbose_tests)` in `test_quadinterpolator.cpp`. When should `cout` be used with `verbose_tests`, vs. the more common `mfem::out`? There is usage of `mfem::out` `if (verbose_tests)`. Should we add `if (verbose_tests)` in addition to the change to `mfem::out`? I suppose unit tests should rely on `REQUIRE` statements to check conditions, and output should be unnecessary but possible in the case `if (verbose_tests)`. If so, `cout` could also be changed in `test_quadinterpolator.cpp` and `test_var_order.cpp`, along with use of `if (verbose_tests)`....</small>

<a href='https://github.com/mfem/mfem/pull/5203' target='_blank'>View Comment</a>