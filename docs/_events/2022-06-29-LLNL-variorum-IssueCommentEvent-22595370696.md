---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/1597518?"
user: tpatki
date: 2022-06-29
repo_name: LLNL/variorum
html_url: https://github.com/LLNL/variorum/pull/265
repo_url: https://github.com/LLNL/variorum
---

<a href='https://github.com/tpatki' target='_blank'>tpatki</a> commented on issue <a href='https://github.com/LLNL/variorum/pull/265' target='_blank'>LLNL/variorum#265</a>.

<small>Decided to go with wrapping around the jansson library, because of amount of existing code that uses the original API. Changing it to encode/decode with strings will mean changing Caliper, Kokkos, Flux and LDMS integrations, and significantly more amount of per-architecture code changes for each internal JSON API. Easier solution at present is to wrap around jansson. ...</small>

<a href='https://github.com/LLNL/variorum/pull/265' target='_blank'>View Comment</a>