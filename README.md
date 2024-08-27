[![Mathematica](https://img.shields.io/badge/Wolfram-Mathematica-DD1100?logo=wolfram-mathematica&logoColor=DD1100)](https://www.wolfram.com/mathematica/)
[![View notebooks](https://wolfr.am/HAAhzkRq)](https://wolfr.am/1mXmN5DaF)

# Non-Hermitian Fermi-Dirac Distribution in Persistent Current Transport

![Distribution Sketch](DistributionSketch.png)

This repository contains the code developed to accompany the Letter titled *Non-Hermitian Fermi-Dirac Distribution in Persistent Current Transport* [[1](#refer-anchor-1)].

## Contents

- `SNS.ipynb`: A phase-biased superconducting-normal-superconducting (SNS) junction.
- `Ring.ipynb`: A normal ring threaded by a magnetic flux.
- `NonHermitianFermiDiracPersistentCurrent.nb`: *Mathematica* notebook ([view online](https://wolfr.am/1mXmN5DaF)) for symbolic derivation of the non-Hermitian Fermi-Dirac distribution and relevant analytical calculations.

## Usage

To run the Jupyter notebooks, ensure you have [DMRGpy](https://github.com/joselado/dmrgpy) installed. Each notebook is self-contained and provides step-by-step computation leading to the ground state energy and persistent current as a function of the phase. The analysis focuses on the influence of many-body interactions on the persistent currents and scrutinizes the signatures of exceptional points within these systems.

For the *Mathematica* notebook, we demonstrate the symbolic derivation of our formalism, including:
- Derivation and visualization of the non-Hermitian Fermi-Dirac distribution.
- Continuity of the persistent current at exceptional points.
- Analytical expressions and and numerical verifications for Green's function.

This notebook has been featured in the [Wolfram Community](https://community.wolfram.com/groups/-/m/t/3258109) in the editorial columns: [Staff Picks](http://wolfr.am/StaffPicks) and [Publication Materials](http://wolfr.am/PubMat).

## Reference

<div id="refer-anchor-1"></div> 

[1] P.-X. Shen, Z. Lu, J. L. Lado, and M. Trif, [*Non-Hermitian Fermi-Dirac Distribution in Persistent Current Transport*](https://arxiv.org/abs/2403.09569), [Phys. Rev. Lett](https://doi.org/10.1103/PhysRevLett.133.086301). **133**, 086301 (2024).

> Please note that in the final published version of our Letter, there is a minor typo in the sentence located in the lower left corner of page 2: "For isolated and Hermitian systems $`\mathcal{H}_\mathrm{sys}`$, the persistent current $`I_\mathrm{iso}(\phi)`$ **n** the many-body ground state with energy $E_0$ follows [56]," where the word **n** should be **in**. 

## Citation

If you use this code or notebook in your research, please cite our Letter:

```bibtex
@article{Shen2024NonHermitian,
  title = {Non-{{Hermitian Fermi-Dirac Distribution}} in {{Persistent Current Transport}}},
  author = {Shen, Pei-Xin and Lu, Zhide and Lado, Jose L. and Trif, Mircea},
  year = {2024},
  month = aug,
  volume = {133},
  number = {8},
  pages = {086301},
  publisher = {American Physical Society},
  doi = {10.1103/PhysRevLett.133.086301},
  journal = {Physical Review Letters}
}
```