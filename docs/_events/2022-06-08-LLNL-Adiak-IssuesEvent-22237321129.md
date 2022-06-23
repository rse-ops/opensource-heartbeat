---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/10790104?"
user: daboehme
date: 2022-06-08
repo_name: LLNL/Adiak
html_url: https://github.com/LLNL/Adiak/issues/14
repo_url: https://github.com/LLNL/Adiak
---

<a href='https://github.com/daboehme' target='_blank'>daboehme</a> closed issue <a href='https://github.com/LLNL/Adiak/issues/14' target='_blank'>LLNL/Adiak#14</a>.

<p>Memory leak</p><small>When running the clang sanitizers in a code using Adiak, I got a bunch of leaked memory errors.  While they are all different stack traces, at the root they are all coming from `adiak_type_to_string`.  This was with version f6787c0 of the code.  It seems like whover is calling `adiak_type_to_string` needs to free the buffer when it's done....</small><a href='https://github.com/LLNL/Adiak/issues/14' target='_blank'>View Comment</a>