---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5720676?"
user: markcmiller86
date: 2026-02-06
repo_name: HDFGroup/hdf5
html_url: https://github.com/HDFGroup/hdf5/issues/6153
repo_url: https://github.com/HDFGroup/hdf5
---

<a href='https://github.com/markcmiller86' target='_blank'>markcmiller86</a> commented on issue <a href='https://github.com/HDFGroup/hdf5/issues/6153' target='_blank'>HDFGroup/hdf5#6153</a>.

<small>What @Dave-Allured is suggesting reminds me of something similar I have considered for the Silo library (a library which typically writes a large variety of 1,2 and 3 dimensioinal, 32/64 bit integer and 32/64 bit floating point data to a Silo "database" and wanting a way for data producers to define compression *strategies* that invoke different filters with different parameters depending on various data attributes. (e.g. compress 2D, 32-bit integer data with szip with entropy-level=2, do not compress any 1D datasets, compress 4D double precision data where slowest dim size <=3 with ZFP filter in rate mode and rate=3.5, etc). I could imagine some standardized, yaml-like configuration string similar to how GitHub actions are specified....</small>

<a href='https://github.com/HDFGroup/hdf5/issues/6153' target='_blank'>View Comment</a>