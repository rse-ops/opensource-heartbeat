---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/20131404?"
user: cmoussa1
date: 2023-01-17
repo_name: flux-framework/flux-accounting
html_url: https://github.com/flux-framework/flux-accounting/issues/306
repo_url: https://github.com/flux-framework/flux-accounting
---

<a href='https://github.com/cmoussa1' target='_blank'>cmoussa1</a> closed issue <a href='https://github.com/flux-framework/flux-accounting/issues/306' target='_blank'>flux-framework/flux-accounting#306</a>.

<p>[refactoring]: change Python bindings to `return` information instead of printing to STDOUT</p><small>While working on #186, I noticed that my branch was becoming increasingly large and probably _very_ inconvenient to review when it becomes ready to post as a PR. This is due to the significant refactoring required for the Python bindings (i.e the `Accounting` class) to interact with the new Python service that interacts with the Flux broker. This refactoring includes changing a number of functions in the class that currently emit output via `print()` statements to instead return this information to the caller, where it will then be the caller's responsibility to get the information returned by the function and then `print()`. Some of this refactoring involves very slight changes to some of the functions themselves. ...</small><a href='https://github.com/flux-framework/flux-accounting/issues/306' target='_blank'>View Comment</a>