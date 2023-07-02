---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-06-30
repo_name: CEED/libCEED
html_url: https://github.com/CEED/libCEED/pull/1245
repo_url: https://github.com/CEED/libCEED
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/CEED/libCEED/pull/1245' target='_blank'>CEED/libCEED#1245</a>.

<small>So `gcc -shared` and `clang -shared` on Debian also produce `+x`, I assume for legacy reasons. I guess we could leave it to Debian to remove those, but I just don't see any point in having them be executable when it can't be executed. We need to specify the permissions (and `install` always does) because some people have `umask 077` and you don't want that to yield an install that's broken for others....</small>

<a href='https://github.com/CEED/libCEED/pull/1245' target='_blank'>View Comment</a>