---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/17935880?"
user: jamiebramwell
date: 2024-02-15
repo_name: LLNL/serac
html_url: https://github.com/LLNL/serac/issues/1080
repo_url: https://github.com/LLNL/serac
---

<a href='https://github.com/jamiebramwell' target='_blank'>jamiebramwell</a> open issue <a href='https://github.com/LLNL/serac/issues/1080' target='_blank'>LLNL/serac#1080</a>.

<p>Investigate why DSuperLU can't be used when systems are resized</p><small>              I had some issues with SuperLU in the tests where if the matrix was resized, then SuperLU wouldn't work.  This is an issue in `SolidMechanics::warmStartDisplacement()` where only the displacements are updated without the LM block.  I only tested with strumpack and SuperLU, but if MUMPS/Pardiso/etc. are added to serac in the future, this macro may need to be updated......</small><a href='https://github.com/LLNL/serac/issues/1080' target='_blank'>View Comment</a>