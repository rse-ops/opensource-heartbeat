---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/15018133?"
user: gardner48
date: 2024-03-11
repo_name: Homebrew/homebrew-core
html_url: https://github.com/Homebrew/homebrew-core/pull/165191
repo_url: https://github.com/Homebrew/homebrew-core
---

<a href='https://github.com/gardner48' target='_blank'>gardner48</a> commented on issue <a href='https://github.com/Homebrew/homebrew-core/pull/165191' target='_blank'>Homebrew/homebrew-core#165191</a>.

<small>The test failures are due to a [change in v7.0](https://github.com/LLNL/sundials/blob/2abd63bd6cbc354fb4861bba8e98d0b95d65e24a/CHANGELOG.md?plain=1#L108) where programs must now link against the `sundials_core` library. Updating [this line](https://github.com/Homebrew/homebrew-core/blob/f909998adf9736c3339071b7565c7d11937d7425/Formula/s/sundials.rb#L56) to include `-lsundials_core` should resolve the problem.  ...</small>

<a href='https://github.com/Homebrew/homebrew-core/pull/165191' target='_blank'>View Comment</a>