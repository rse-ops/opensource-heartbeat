---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/660149?"
user: trws
date: 2022-06-29
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/31361
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/trws' target='_blank'>trws</a> commented on issue <a href='https://github.com/spack/spack/issues/31361' target='_blank'>spack/spack#31361</a>.

<small>It's mildly annoying, but we can actually control for that @haampie. We need to make a directory that symlinks, *sigh*, to the actual gcc path we want from a path that looks like `$PREFIX/include|lib/gcc/$PLATFORM/$VERSION/` to do it, but then `--gcc-toolchain` works.  That's how we maintain clang's with a pre-set default gcc-toolchain in LC for example, the `LIBCXX_GCC_TOOLCHAIN` flag to the cmake needs the same thing.  It's on my list for the llvm package, but that darned directory structure does not make it a nice thing to do, especially for a one-off....</small>

<a href='https://github.com/spack/spack/issues/31361' target='_blank'>View Comment</a>