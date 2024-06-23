---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/874707?"
user: SteVwonder
date: 2024-06-17
repo_name: spudlyo/clipetty
html_url: https://github.com/spudlyo/clipetty/issues/30
repo_url: https://github.com/spudlyo/clipetty
---

<a href='https://github.com/SteVwonder' target='_blank'>SteVwonder</a> commented on issue <a href='https://github.com/spudlyo/clipetty/issues/30' target='_blank'>spudlyo/clipetty#30</a>.

<small>I had the same issue.  Walking through the code, my issue turned out to be due to `TMUX`, `TERM`, and `SSH_TTY` env vars returning as `nil` from the call to `(getenv "<ENVVAR>" (selected-frame))`.  Dropping the `(selected-frame)` bit makes things work again:...</small>

<a href='https://github.com/spudlyo/clipetty/issues/30' target='_blank'>View Comment</a>