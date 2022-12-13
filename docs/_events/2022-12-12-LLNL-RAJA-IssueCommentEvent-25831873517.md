---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-12-12
repo_name: LLNL/RAJA
html_url: https://github.com/LLNL/RAJA/pull/1404
repo_url: https://github.com/LLNL/RAJA
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/LLNL/RAJA/pull/1404' target='_blank'>LLNL/RAJA#1404</a>.

<small>The issue here is probably that the required alignment of long double on the device really is only 8 bytes, in which case the correct value there is technically 8 bytes.  It's unfortunate, but for a part that doesn't natively support 16-byte intrinsic types it's probably correct.  I'd guess we'd want to pick a standard size for this, ensure it's always large enough with a static_assert as you mention above @MrBurmark, and move on.  It should be a per-host-architecture choice at worst, so not too bad.  Honestly I don't think I've ever seen an arch with a value over 32 either, so if we're ok with wasting a few bytes we could probably get away with that, it would also give more storage we could use for a more efficient inline storage of functors.  Either way, the general solution looks right, but I'd make it *one* value that gets used for both, and not backend specific so we can avoid this coming back....</small>

<a href='https://github.com/LLNL/RAJA/pull/1404' target='_blank'>View Comment</a>