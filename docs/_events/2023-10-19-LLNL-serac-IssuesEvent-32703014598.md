---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/17935880?"
user: jamiebramwell
date: 2023-10-19
repo_name: LLNL/serac
html_url: https://github.com/LLNL/serac/issues/1014
repo_url: https://github.com/LLNL/serac
---

<a href='https://github.com/jamiebramwell' target='_blank'>jamiebramwell</a> open issue <a href='https://github.com/LLNL/serac/issues/1014' target='_blank'>LLNL/serac#1014</a>.

<p>Use correct primal values in the sensitivity calls</p><small>As written, the sensitivity calculation calls in the `HeatTransfer` and `SolidMechanics` modules will not use the correct primal field values (e.g. temperature) during the backward adjoint pass. See https://github.com/LLNL/serac/blob/a2d7924235565ceccb2a7b341951680aa3afb679/src/serac/physics/heat_transfer.hpp#L921-L927 ....</small><a href='https://github.com/LLNL/serac/issues/1014' target='_blank'>View Comment</a>