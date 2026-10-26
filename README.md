# iteraSim Eddy — release binaries

Installers for **iteraSim Eddy**, the AI agent that sets up, runs and repairs
OpenFOAM CFD simulations.

Get the latest build from the [Releases](../../releases) page, or from
[iterasim.in](https://www.iterasim.in/eddy.html).

| Platform | File | Install |
|---|---|---|
| Linux | `iteraSim-Eddy-<version>.AppImage` | `chmod +x` it and run it. No root, no dependencies. |
| Windows | `iteraSim-Eddy-Setup-<version>.exe` | Run the installer. The backend runs in WSL2. |
| macOS | — | Not yet. On the roadmap. |

Eddy is the interface; **OpenFOAM is the engine**. Install OpenFOAM v2306 or
newer separately — Eddy detects it at launch and shows the version it picked in
the status bar.

- Documentation: <https://iterasim.github.io/iteraSim_GUI/>
- Questions and bug reports: <https://github.com/iterasim/eddy-community/discussions>
- Contact: info@iterasim.in

This repository holds release artifacts only; the application source is private.

---

© iteraSim, Zürich. OPENFOAM® is a registered trade mark of OpenCFD Limited,
producer and distributor of the OpenFOAM software via www.openfoam.com.
iteraSim is not approved or endorsed by OpenCFD Limited.
