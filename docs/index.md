<head>
  <meta charset="UTF-8">
  <meta name="description" content="AMD ROCm documentation">
  <meta name="keywords" content="documentation, guides, installation, compatibility, support,
  reference, ROCm, AMD">
</head>

# AMD ROCm™ documentation

Welcome to the ROCm docs home page! If you're new to ROCm, you can review the following
resources to learn more about our products and what we support:

* [What is ROCm?](./what-is-rocm.rst)
* [Release notes](./about/release-notes.md)

You can install ROCm on our Radeon™, Radeon™ PRO, and Instinct™ GPUs. If you're using Radeon
GPUs, we recommend reading the
{doc}`Radeon-specific ROCm documentation<radeon:index>`.

For hands-on applications, refer to our [ROCm blogs](https://rocm.blogs.amd.com/) site.

Our documentation is organized into the following categories:

::::{grid} 1 2 2 2
:class-container: rocm-doc-grid

:::{grid-item-card}
:class-card: sd-text-black
:img-top: ./data/banner-installation.jpg
:img-alt: Install documentation
:padding: 2

* Linux
  * {doc}`Quick start guide<rocm-install-on-linux:tutorial/quick-start>`
  * {doc}`Linux install guide<rocm-install-on-linux:how-to/native-install/index>`
  * {doc}`Package manager integration<rocm-install-on-linux:how-to/native-install/package-manager-integration>`
  * {doc}`Install Docker containers<rocm-install-on-linux:how-to/docker>`
  * {doc}`ROCm & Spack<rocm-install-on-linux:how-to/spack>`
* Windows
  * {doc}`Windows install guide<rocm-install-on-windows:how-to/install>`
  * {doc}`Application deployment guidelines<rocm-install-on-windows:conceptual/deployment-guidelines>`
* [Deep learning frameworks](./how-to/deep-learning-rocm.rst)
  * {doc}`PyTorch for ROCm<rocm-install-on-linux:how-to/3rd-party/pytorch-install>`
  * {doc}`TensorFlow for ROCm<rocm-install-on-linux:how-to/3rd-party/tensorflow-install>`
  * {doc}`JAX for ROCm<rocm-install-on-linux:how-to/3rd-party/jax-install>`
  * {doc}`MAGMA for ROCm<rocm-install-on-linux:how-to/3rd-party/magma-install>`
:::

:::{grid-item-card}
:class-card: sd-text-black
:img-top: ./data/banner-compatibility.jpg
:img-alt: Compatibility information
:padding: 2

* [Compatibility matrix](./compatibility/compatibility-matrix.rst)
* {doc}`System requirements (Linux)<rocm-install-on-linux:reference/system-requirements>`
* {doc}`System requirements (Windows)<rocm-install-on-windows:reference/system-requirements>`
* {doc}`Third-party support<rocm-install-on-linux:reference/3rd-party-support-matrix>`
* {doc}`User/kernel space<rocm-install-on-linux:reference/user-kernel-space-compat-matrix>`
* {doc}`Docker<rocm-install-on-linux:reference/docker-image-support-matrix>`
* [OpenMP](./about/compatibility/openmp.md)
* [Precision support](./compatibility/precision-support.rst)
* {doc}`ROCm on Radeon GPUs<radeon:index>`
:::

<!-- markdownlint-disable MD051 -->
:::{grid-item-card}
:class-card: sd-text-black
:img-top: ./data/banner-reference.jpg
:img-alt: Reference documentation
:padding: 2

* [API libraries](./reference/api-libraries.md)
  * [Artificial intelligence](#artificial-intelligence-apis)
  * [C++ primitives](#cpp-primitives)
  * [Communication](#communication-libraries)
  * [Math](#math-apis)
  * [Random number generators](#random-number-apis)
  * [HIP runtime](#hip-runtime)
* [Tools](./reference/rocm-tools.md)
  * [Development](#development-tools)
  * [Performance analysis](#performance-analysis)
  * [System](#system-tools)
* [Environment Variables](./reference/env-variables.rst)
* [Hardware specifications](./reference/gpu-arch-specs.rst)
:::
<!-- markdownlint-enable MD051 -->

:::{grid-item-card}
:class-card: sd-text-black
:img-top: ./data/banner-howto.jpg
:img-alt: How-to documentation
:padding: 2

* [Using ROCm for AI](./how-to/rocm-for-ai/index.rst)
* [Fine-tuning LLMs and inference optimization](./how-to/llm-fine-tuning-optimization/index.rst)
* [System tuning for various architectures](./how-to/tuning-guides.md)
  * [MI100](./how-to/tuning-guides/mi100.md)
  * [MI200](./how-to/tuning-guides/mi200.md)
  * [RDNA2](./how-to/tuning-guides/w6000-v620.md)
* [GPU-enabled MPI](./how-to/gpu-enabled-mpi.rst)
* [Using compiler features](./conceptual/compiler-topics.md)
  * [Using AddressSanitizer](./conceptual/using-gpu-sanitizer.md)
  * [Compiler disambiguation](./conceptual/compiler-disambiguation.md)
  * [OpenMP support in ROCm](./about/compatibility/openmp.md)
* [Setting the number of CUs](./how-to/setting-cus)  
* [System level debugging](./how-to/system-debugging.md)
* [GitHub examples](https://github.com/amd/rocm-examples)
:::

:::{grid-item-card}
:class-card: sd-text-black
:img-top: ./data/banner-conceptual.jpg
:img-alt: Conceptual documentation
:padding: 2

* [GPU architecture](./conceptual/gpu-arch.md)
  * [MI100](./conceptual/gpu-arch/mi100.md)
  * [MI250](./conceptual/gpu-arch/mi250.md)
  * [MI300](./conceptual/gpu-arch/mi300.md)
* [GPU memory](./conceptual/gpu-memory.md)
* [File structure (Linux FHS)](./conceptual/file-reorg.md)
* [GPU isolation techniques](./conceptual/gpu-isolation.md)
* [Using CMake](./conceptual/cmake-packages.rst)
* [ROCm & PCIe atomics](./conceptual/More-about-how-ROCm-uses-PCIe-Atomics.rst)
* [Inception v3 with PyTorch](./conceptual/ai-pytorch-inception.md)
* [Inference optimization with MIGraphX](./conceptual/ai-migraphx-optimization.md)
:::

::::
