---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2024-03-29
repo_name: desul/desul
html_url: https://github.com/desul/desul/issues/120
repo_url: https://github.com/desul/desul
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/desul/desul/issues/120' target='_blank'>desul/desul#120</a>.

<small>This is a significantly different case than when using relaxed to protect a reduction. That said, we do have an issue here.  Currently using this with acq_rel or similar atomics should work just fine, because they'll add the appropriate fences around it, but relaxed as it sits is wrong in that test.  Not only because this is relaxed though, it's because both this is relaxed and the memory operations inside the `SuperScalar` class are non-atomic, so when using a relaxed memory order on the outer atomic there's no flush to ensure those writes leave the inner caches of the writer....</small>

<a href='https://github.com/desul/desul/issues/120' target='_blank'>View Comment</a>