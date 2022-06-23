---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/1597518?"
user: tpatki
date: 2022-06-16
repo_name: tpatki/PerfFlowAspect
html_url: https://github.com/tpatki/PerfFlowAspect/commit/9649c8932985a4e96d07e4e3bf76781546ef1e74
repo_url: https://github.com/tpatki/PerfFlowAspect
---

<a href='https://github.com/tpatki' target='_blank'>tpatki</a> pushed to <a href='https://github.com/tpatki/PerfFlowAspect' target='_blank'>tpatki/PerfFlowAspect</a>

<small>Migrating to CMake build for C/C++ (#46)

* update c build steps for github actions

- add configs for generating cmake and pc files for integrating PerfFlowAspect
  into other projects
- install sharness.sh and unit test driver script for unit tests
- set CXX compiler to clang++ in github workflow config

* switch CI to ubuntu 20, update weave source for >=clang9

older clang broken in ubuntu 18.04

* fix tests

- install just sharness.sh script instead of directory
- update unit test driver file with correct paths to sharness.sh and runtime
  library

* update unit test driver to be configurable by CMake

- no need to install sharness.sh, reference it using CMake variables
- export LD_LIBRARY_PATH to runtime dir in build dir or lib dir in install dir,
  two different locations depending on if project is built or installed

* check for minimum clang++ version

CMAKE_CXX_COMPILER must be clang >= 9.0

* Update README in src/c

Co-authored-by: Tapasya Patki <patki1@llnl.gov></small>

<a href='https://github.com/tpatki/PerfFlowAspect/commit/9649c8932985a4e96d07e4e3bf76781546ef1e74' target='_blank'>View Commit</a>