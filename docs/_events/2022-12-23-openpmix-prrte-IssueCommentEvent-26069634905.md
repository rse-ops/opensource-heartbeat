---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/7818666?"
user: hppritcha
date: 2022-12-23
repo_name: openpmix/prrte
html_url: https://github.com/openpmix/prrte/issues/1628
repo_url: https://github.com/openpmix/prrte
---

<a href='https://github.com/hppritcha' target='_blank'>hppritcha</a> commented on issue <a href='https://github.com/openpmix/prrte/issues/1628' target='_blank'>openpmix/prrte#1628</a>.

<small>Turns out that the vendor simplified things somewhat starting with an updated CXI provider.  As long as a process is a child of slurmstepd or the pals equivalent of slurmstepd that the env. is set up such that the CXI provider will use the right VNI credentials under the covers if the application doesn't explicitly provide them in the call to ```fi_domain``` and ```fi_endpoint```.  But, for the general case we would want to modify pnet/sshot to crack these env. variables and pass them along in a PMIx way to the application processes....</small>

<a href='https://github.com/openpmix/prrte/issues/1628' target='_blank'>View Comment</a>