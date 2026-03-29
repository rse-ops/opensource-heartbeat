---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/4440062?"
user: mplegendre
date: 2026-03-27
repo_name: llnl/Spindle
html_url: https://github.com/llnl/Spindle/pull/148
repo_url: https://github.com/llnl/Spindle
---

<a href='https://github.com/mplegendre' target='_blank'>mplegendre</a> commented on issue <a href='https://github.com/llnl/Spindle/pull/148' target='_blank'>llnl/Spindle#148</a>.

<small>I went over the /bin/.. case in detail, and it looks like we handle it okay. There's definitely some oddities with spindle putting ".." into an internal variable named 'file'. But we ultimately always supported spindle operations on directories (even if that wasn't common), and ".." just gets treated like other directories and handled correctly. ...</small>

<a href='https://github.com/llnl/Spindle/pull/148' target='_blank'>View Comment</a>