---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/32752943?"
user: corbett5
date: 2024-08-13
repo_name: JuliaSparse/SparseArrays.jl
html_url: https://github.com/JuliaSparse/SparseArrays.jl/pull/557
repo_url: https://github.com/JuliaSparse/SparseArrays.jl
---

<a href='https://github.com/corbett5' target='_blank'>corbett5</a> commented on issue <a href='https://github.com/JuliaSparse/SparseArrays.jl/pull/557' target='_blank'>JuliaSparse/SparseArrays.jl#557</a>.

<small>Ahh silly me, I didn't realize floats weren't supported. Well I do have a use case where the default tolerance for a Float32 matrix (as computed in Julia) is ridiculously large. My intuition is that the default tolerance should be `DBL_EPSILON` since this is more conservative and would accurately reflect floating point errors that are incurred during the decomposition, ignoring floating point errors that may or may not have occurred in calculating the original matrix entries themselves....</small>

<a href='https://github.com/JuliaSparse/SparseArrays.jl/pull/557' target='_blank'>View Comment</a>