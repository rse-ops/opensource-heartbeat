---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/12700975?"
user: dylan-copeland
date: 2023-02-22
repo_name: mfem/mfem
html_url: https://github.com/mfem/mfem/pull/3088
repo_url: https://github.com/mfem/mfem
---

<a href='https://github.com/dylan-copeland' target='_blank'>dylan-copeland</a> commented on issue <a href='https://github.com/mfem/mfem/pull/3088' target='_blank'>mfem/mfem#3088</a>.

<small>Thank you @IdoAkkerman for your suggestions. You are right that the `NNLS` class could be improved. It is adapted from another code outside MFEM, without the MFEM `Solver` class in mind. Some issues with making it derived from the `Solver` class are (i) as you mentioned, `SolveNNLS` would need to become the `Mult` function, assuming that the upper and lower bounds should be computed as in that function, which limits the generality of usage of `NNLS`; (ii) the operator must be a `DenseMatrix` in order to access entries; (iii) `NormalizeConstraints` scales the rows of the `DenseMatrix`....</small>

<a href='https://github.com/mfem/mfem/pull/3088' target='_blank'>View Comment</a>