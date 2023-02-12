---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/14316120?"
user: bwpriest
date: 2023-02-09
repo_name: LLNL/ygm
html_url: https://github.com/LLNL/ygm/pull/128
repo_url: https://github.com/LLNL/ygm
---

<a href='https://github.com/bwpriest' target='_blank'>bwpriest</a> commented on issue <a href='https://github.com/LLNL/ygm/pull/128' target='_blank'>LLNL/ygm#128</a>.

<small>I removed `ygm::container::bag::for_all_pairs()` due to the objections that the name is confusing. Instead I added some constexpr metaprogramming to `ygm::container::bag::for_all()` that checks at compile time if the `Item` class is a pair, and if the lambda is invocable with a `(Item::first_type &, Item::second_type &)` signature, in which case it separates the pair. Otherwise, it expects the original signature....</small>

<a href='https://github.com/LLNL/ygm/pull/128' target='_blank'>View Comment</a>