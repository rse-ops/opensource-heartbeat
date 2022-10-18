---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/25011573?"
user: jeremylt
date: 2022-10-17
repo_name: jeremylt/LFAToolkit.jl
html_url: https://github.com/jeremylt/LFAToolkit.jl/issues/47
repo_url: https://github.com/jeremylt/LFAToolkit.jl
---

<a href='https://github.com/jeremylt' target='_blank'>jeremylt</a> closed issue <a href='https://github.com/jeremylt/LFAToolkit.jl/issues/47' target='_blank'>jeremylt/LFAToolkit.jl#47</a>.

<p>Use FastGaussQuadrature</p><small>Computing with hundreds of quadrature points is rather slow and I suspect our quadrature nodes are not quite accurate to machine precision. Using lots of points is convenient for plotting and sometimes may be useful for the harmonic transform. I think we should discard the basic Newton algorithm and just use [FastGaussQuadrature](https://juliapackages.com/p/fastgaussquadrature), which can compute millions of points in a fraction of a second. This may come at small precompilation overhead to new runs, but it's minor and fast, accurate quadrature is worth it....</small><a href='https://github.com/jeremylt/LFAToolkit.jl/issues/47' target='_blank'>View Comment</a>