---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/3303?"
user: jedbrown
date: 2023-12-20
repo_name: jedbrown/llvm-jit-ptx
html_url: https://github.com/jedbrown/llvm-jit-ptx/issues/1
repo_url: https://github.com/jedbrown/llvm-jit-ptx
---

<a href='https://github.com/jedbrown' target='_blank'>jedbrown</a> open issue <a href='https://github.com/jedbrown/llvm-jit-ptx/issues/1' target='_blank'>jedbrown/llvm-jit-ptx#1</a>.

<p>math library support</p><small>I'm still having trouble using the `libm` feature to `num-traits` because I've been unable to capture IR for `libm`. However, `libm` is known to have rather poor performance and Enzyme won't automatically know how to differentiate it. There is some [prior art in cuda-std](https://github.com/Rust-GPU/Rust-CUDA/blob/master/crates/cuda_std/src/float.rs), but it's not compatible with `num-traits`. It does have a ["libm override" feature](https://github.com/Rust-GPU/Rust-CUDA/commit/39edde483891d5b383b83032a83618a9f7d3d80c), but I think people generally don't want to use `libm` on the host either (it's typically slow). In any case, the intrinsic approach needed [special support in `rustc_codegen_nvvm`](https://github.com/Rust-GPU/Rust-CUDA/blob/master/crates/rustc_codegen_nvvm/src/ctx_intrinsics.rs#L304), so we may need to upstream something similar into `rustc`. I think the preferred ergonomics would be a `cuda` feature added to `num-traits`....</small><a href='https://github.com/jedbrown/llvm-jit-ptx/issues/1' target='_blank'>View Comment</a>