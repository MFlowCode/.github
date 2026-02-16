<p align="center">
  <img src="banner.png" alt="MFC Banner" width="500"/>
</p>

<h3 align="center">Exascale multiphase flow solver - 2025 Gordon Bell Prize Finalist</h3>

<p align="center">
  <a href="https://github.com/MFlowCode/MFC">
    <img src="https://img.shields.io/github/stars/MFlowCode/MFC?style=social" alt="GitHub stars"/>
  </a>
</p>

**MFC** conducted the [largest known public CFD simulation](https://arxiv.org/abs/2505.07392) at **200 trillion grid points** on **43,000+ AMD APUs** on [El Capitan](https://hpc.llnl.gov/hardware/compute-platforms/el-capitan) and **33,000+ AMD GPUs** on [Frontier](https://www.olcf.ornl.gov/frontier/). It is written in ~40K lines of Fortran with [Fypp](https://fypp.readthedocs.io/en/stable/fypp.html) metaprogramming.

### Get started

- **Repository**: [MFlowCode/MFC](https://github.com/MFlowCode/MFC) (pinned below)
- **Documentation**: [mflowcode.github.io](https://mflowcode.github.io/documentation/index.html)
- **Quick start**: [Getting Started guide](https://mflowcode.github.io/documentation/getting-started.html) or [open a Codespace](https://github.com/codespaces/new?hide_repo_select=true&ref=master&repo=MFlowCode%2FMFC)

### Capabilities

- **Exascale GPU performance** - Ideal weak scaling on El Capitan (MI300A), Frontier (MI250X), and Alps (GH200). Near compute-roofline. [Compile-time case optimization](https://mflowcode.github.io/documentation/running.html) for up to 10x speedup.
- **Multi-phase/physics** - 4, 5, and 6-equation models, phase change, surface tension, bubble dynamics, MHD, relativistic MHD, hyper/hypoelasticity, chemistry, and Euler-Lagrange particle tracking.
- **Portable** - NVIDIA and AMD GPUs, CPUs, laptops to exascale. Docker, Codespaces, Homebrew, and [16+ HPC system templates](https://mflowcode.github.io/documentation/running.html).

### Community

MFC nucleated from [Tim Colonius's group](https://colonius.caltech.edu/) at Caltech. The [Bryngelson Group](https://comp-physics.group) at Georgia Tech leads development, with close collaborators at [Brown](https://vivo.brown.edu/display/mrodri97) (Rodriguez), [WPI](https://www.wpi.edu/people/faculty/agnanaskandan) (Gnanaskandan), and others.

MFC is a SPEChpc benchmark candidate, part of the JSC JUPITER Early Access Program, and used OLCF Frontier and LLNL El Capitan early access systems.

Questions? Join the [MFC Slack](https://join.slack.com/t/mflowcode/shared_invite/zt-y75wibvk-g~zztjknjYkK1hFgCuJxVw) or contact [Spencer Bryngelson](mailto:shb@gatech.edu).
