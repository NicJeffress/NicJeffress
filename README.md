# Nicolas (Nic) Jeffress

Mechanical engineer turned physical oceanographer. I recently finished my PhD at Duke University, where I studied how waves lose energy over very rough coral reefs and how to represent that bottom friction in wave models. I'm based in Santa Barbara, CA.

I care about making scientific models trustworthy and affordable to run: testing every change carefully and getting the same answer on any machine.

![Idealized fringing reef with a pass, used for COAWST ensembles](https://raw.githubusercontent.com/NicJeffress/idealized-reef/main/figures/a15_bathymetry.png)

### What I work on

- Coupled wave and circulation modeling (COAWST, ROMS, SWAN) and particle tracking (ROMSPath)
- Testing, extending and speeding up large Fortran model codes
- Reproducible builds in containers (Docker, Apptainer) with automated checks in GitHub Actions
- Ensemble runs on Google Cloud (Compute Engine, Cloud Batch, Spot machines) and HPC (512-core runs on SDSC Expanse)
- Bathymetry merging, satellite imagery analysis, and field data from ADCPs and pressure sensors
- Python, MATLAB, Fortran, C/C++, MPI, Linux/bash

### Featured projects

- **[coawst-cloud](https://github.com/NicJeffress/coawst-cloud)**: a containerized build of COAWST v3.9 for running coastal ocean ensembles on any machine or on Google Cloud. It adds 29 documented and tested patches, fixes and extensions I developed while taking COAWST into periodic, vegetated reef setups, which I plan to offer upstream. Results are bit-identical on Intel and AMD, restarts are exact so long runs can use Spot machines, and the coupled reef case runs 1.7x faster.
- **[idealized-reef](https://github.com/NicJeffress/idealized-reef)**: a family of idealized coral reef and island simulations (canopy, stratification, solar heating) tested in more than 100 runs, with a lab notebook entry for each. A simulated day costs about $0.15 on Spot machines.
- **[ROMSPath](https://github.com/NicJeffress/ROMSPath)**: my fork of ROMSPath (Hunter et al., 2022), a particle tracking model for ROMS. I added periodic boundaries for idealized reef domains, along with timing and grid fixes checked against a test case with an exact answer, and made it 29 to 43% faster. Each change is its own commit so it can be offered to the original authors.

### Get in touch

I'm open to roles in ocean and coastal modeling, coastal hazard and flood risk, climate research, and ML for weather and climate.
[LinkedIn](https://www.linkedin.com/in/nicolas-jeffress)
