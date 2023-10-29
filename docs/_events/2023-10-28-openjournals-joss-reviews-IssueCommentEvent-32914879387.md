---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-10-28
repo_name: openjournals/joss-reviews
html_url: https://github.com/openjournals/joss-reviews/issues/5097
repo_url: https://github.com/openjournals/joss-reviews
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> commented on issue <a href='https://github.com/openjournals/joss-reviews/issues/5097' target='_blank'>openjournals/joss-reviews#5097</a>.

<small>Sorry about the disruption. For the parallel build, I think it's because the same file names are used for those modules and CMake evidently doesn't know how to use `-J` to control the module output directory. If you made sure that the modules have unique names (either by avoiding copies or by giving them different names), I think the parallel build would work. (Fortran module names are effectively global and to my knowledge, the language doesn't offer namespacing so CMake does something plausible and in signature style, doesn't check for collisions.) This is not a blocker, but it either needs to be fixed or documented....</small>

<a href='https://github.com/openjournals/joss-reviews/issues/5097' target='_blank'>View Comment</a>