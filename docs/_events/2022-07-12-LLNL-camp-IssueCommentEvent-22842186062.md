---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-07-12
repo_name: LLNL/camp
html_url: https://github.com/LLNL/camp/issues/110
repo_url: https://github.com/LLNL/camp
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/LLNL/camp/issues/110' target='_blank'>LLNL/camp#110</a>.

<small>@CameronRutherford, in working on some updates to the cmake here and in RAJA (partly spurred by this but also to fix other issues) I think we may already support this by use of BLT_EXPORT_THIRDPARTY=Off in the cmake configure.  I'm not 100% sure that will remove the library dependency, but it will remove the target from the export.  If that doesn't do it, we'll have to add something to completely prevent camp from linking to the library at all, which is a bit more complicated....</small>

<a href='https://github.com/LLNL/camp/issues/110' target='_blank'>View Comment</a>