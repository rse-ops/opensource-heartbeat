---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/5669480?"
user: balos1
date: 2024-03-22
repo_name: AMReX-Codes/amrex
html_url: https://github.com/AMReX-Codes/amrex/pull/3835
repo_url: https://github.com/AMReX-Codes/amrex
---

<a href='https://github.com/balos1' target='_blank'>balos1</a> commented on issue <a href='https://github.com/AMReX-Codes/amrex/pull/3835' target='_blank'>AMReX-Codes/amrex#3835</a>.

<small>@WeiqunZhang Unfortunately it looks like we setup the [CMake version file for SUNDIALS](https://github.com/LLNL/sundials/blob/main/CMakeLists.txt#L267) with the `SameMajorVersion` [compatibility mode](https://cmake.org/cmake/help/latest/module/CMakePackageConfigHelpers.html#command:write_basic_package_version_file). Im going to change it to `AnyNewerVersion`, but that doesn't fix the problem for 7.0.0.  The workaround is to either do `find_package` twice (once with minimum 6.0.0 and once with minimum 7.0.0, check if `NOT SUNDIALS_FOUND` after the first one), or check the version manually like this:...</small>

<a href='https://github.com/AMReX-Codes/amrex/pull/3835' target='_blank'>View Comment</a>