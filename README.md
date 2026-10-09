<h1 align="center">Alexandros Papagiannakis</h1>

<p align="center">
  <b>Computational systems biology</b> · <b>quantitative imaging</b> · <b>physics of living matter</b>
</p>

<p align="center">
  <a href="https://scholar.google.com/citations?user=sxnPVMcAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://orcid.org/0000-0002-6363-804X"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="https://www.linkedin.com/in/alex-papagiannakis-singlecells/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.ebi.ac.uk/biostudies/bioimages/studies/S-BIAD1658"><img src="https://img.shields.io/badge/Open_Data-BioImage_Archive-00A0A0?style=for-the-badge" alt="BioImage Archive"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/scikit--image-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-image">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter">
</p>

<p align="center">
  <img src="https://github.com/alexSysBio/alexSysBio/blob/main/particle_tracking.gif?raw=1" alt="Single-particle tracking in live cells" width="80%"/>
  <br>
  <sub><i>Single-particle tracking in living cells.</i></sub>
</p>

---

## Research
I work at the interface of cell biology and biophysics, combining experiments, machine learning and mathematical modeling to explain, systematically, how the essential molecules for life self-organize to serve essential functions.

The work spans every level of biological organization, from single molecules to cell communities and tissues. At its core is a simple observation: the essential macromolecular machines of the cell, actively transcribed DNA and actively translated mRNA, interact according to physical laws, and those interactions recur across all living systems. Due to this universality, the physics that link spatiotemporal order to cellular and tissue physiology can be captured in mechanistic frameworks with a broad reach, from fundamental questions about the origins of life to biomedical applications.

| | |
|---|---|
| 🔬 **High-content imaging** | turning raw microscopy into quantitative, time- and space-resolved measurements in individual cells |
| 🤖 **Big-data analysis & ML** | making that extraction robust across conditions and scales, and identifying biologically important variables |
| 📐 **Mathematical modeling** | translating candidate physical mechanisms into predictions that can be tested experimentally |



---

## Open science ⚛️

I am guided by a vision of openly accessible, ethical science that addresses contemporary biomedical and environmental challenges while expanding our quantitative understanding of fundamental biological processes.

**Public imaging datasets**

- [BioImage Archive · S-BIAD1658](https://www.ebi.ac.uk/biostudies/bioimages/studies/S-BIAD1658)
- [BioImage Archive · S-BIAD1350](https://www.ebi.ac.uk/biostudies/bioimages/studies/S-BIAD1350)

---

## Selected publications 📚

<sub>🌟 = first or co-first author</sub>

**🌟 Nonequilibrium polysome dynamics promote chromosome segregation and its coupling to cell growth in *Escherichia coli***
<br><sub>**A. Papagiannakis**, Q. Yu, S.K. Govers, W-H. Lin, N.S. Wingreen, C. Jacobs-Wagner · *eLife* (2025)</sub>
<br><sub>[📄 Paper](https://doi.org/10.7554/eLife.104276.3) · doi:10.7554/eLife.104276.3</sub>

**🌟 Genome concentration limits cell growth and modulates proteome composition in *Escherichia coli***
<br><sub>J. Mäkelä, **A. Papagiannakis**, W-H. Lin, M.C. Lanz, S. Glenn, M. Swaffer, G.K. Marinov, J.M. Skotheim, C. Jacobs-Wagner · *eLife* (2024) 13:RP97465</sub>
<br><sub>[📄 Paper](https://elifesciences.org/articles/97465)</sub>

**🌟 Autonomous metabolic oscillations robustly gate the early and the late cell cycle**
<br><sub>**A. Papagiannakis**, B. Niebel, E.C. Wit, M. Heinemann · *Molecular Cell* (2017) 65(2):285–295</sub>
<br><sub>[📄 Paper](https://pubmed.ncbi.nlm.nih.gov/27989441/)</sub>

**Proximity labeling reveals non-centrosomal microtubule-organizing center components required for microtubule growth and localization**
<br><sub>A.D. Sanchez, T.C. Branon, L.E. Cote, **A. Papagiannakis**, X. Liang, M.A. Pickett, K. Shen, C. Jacobs-Wagner, A.Y. Ting, J.L. Feldman · *Current Biology* (2021) 31(16):3586–3600.e11</sub>
<br><sub>[📄 Paper](https://pubmed.ncbi.nlm.nih.gov/34242576/)</sub>

**🌟 Quantitative characterization of the auxin-inducible degron: a guide for dynamic protein depletion in single yeast cells**
<br><sub>**A. Papagiannakis**, J.J. de Jonge, Z. Zhang, M. Heinemann · *Scientific Reports* (2017) 7:4704</sub>
<br><sub>[📄 Paper](https://www.nature.com/articles/s41598-017-04791-6)</sub>

<p align="left"><a href="https://scholar.google.com/citations?user=sxnPVMcAAAAJ&hl=en"><b>→ Full publication list on Google Scholar</b></a></p>

---

## Open-source toolkit 🌳

A Python stack for quantitative single-cell microscopy — from raw `.nd2` frames to curated masks, tracked lineages and simulated ground truth. All repositories are at [github.com/alexSysBio](https://github.com/alexSysBio).

<details open>
<summary><b>🖼️ &nbsp;Image import & preprocessing</b></summary>
<br>

| Public repository | What it does |
|---|---|
| [**omePyfun**](https://github.com/alexSysBio/omePyfun) | Reads `.nd2` microscopy files into multidimensional NumPy arrays and writes them as OME-Zarr pyramids |
| [**NDtwoPy**](https://github.com/alexSysBio/NDtwoPy) | A `pims_nd2` reader supporting different image-iteration axes |
| [**UnBack**](https://github.com/alexSysBio/UnBack) | Background subtraction for fluorescence microscopy images |
| [**UnDrift**](https://github.com/alexSysBio/UnDrift) | Correction of stage and sample drift in time-lapse acquisitions |
| [**Image-analysis**](https://github.com/alexSysBio/Image-analysis) | General-purpose microscopy analysis functions: `.nd2` import, background correction, medial-axis estimation |

</details>

<details open>
<summary><b>🧫 &nbsp;Segmentation, masks & cell morphology</b></summary>
<br>

| Public repository | What it does |
|---|---|
| [**PycellMask**](https://github.com/alexSysBio/PycellMask) | Brings cell segmentation masks from external tools and software into Python |
| [**SuperMaskClass**](https://github.com/alexSysBio/SuperMaskClass) | Classification of individual cell instances |
| [**ManuCure**](https://github.com/alexSysBio/ManuCure) | A PyQt5 graphical interface for the manual curation of cell labels |
| [**PyMedialAxis**](https://github.com/alexSysBio/PyMedialAxis) | Custom functions for drawing the medial cell axis |
| [**PyntensityProfile**](https://github.com/alexSysBio/PyntensityProfile) | Generation of intensity profiles from single cells |
| [**2DCellProject**](https://github.com/alexSysBio/2dCellProject) | Projection and plotting of single-cell arrays in two dimensions |

</details>

<details open>
<summary><b>🎯 &nbsp;Tracking, lineages & single-cell statistics</b></summary>
<br>

| Public repository | What it does |
|---|---|
| [**sptPy**](https://github.com/alexSysBio/sptPy) | A single-particle tracking class |
| [**ObtrackerPy**](https://github.com/alexSysBio/ObtrackerPy) | Tracking of objects in time-lapse images |
| [**microlineagePy**](https://github.com/alexSysBio/microlineagePy) | Linking of cells into lineages |
| [**AgarlapsePy**](https://github.com/alexSysBio/AgarlapsePy) | Classes and functions for fluorescence statistics of cell lineages |

</details>

<details open>
<summary><b>📐 &nbsp;Simulation & modeling</b></summary>
<br>

| Public repository | What it does |
|---|---|
| [**DiffractionPySim**](https://github.com/alexSysBio/DiffractionPySim) | Simulation of diffraction-limited spots in the presence of Gaussian noise |
| [**PySimuNS**](https://github.com/alexSysBio/PySimuNS) | Particle simulations with and without cell confinement and nucleoid exclusion |
| [**membranePySim**](https://github.com/alexSysBio/membraneSimPy) | Simulation of membrane-associated dynamics |
| [**areaOverPy**](https://github.com/alexSysBio/areaOverPy) | Numerical simulation of cell-area growth under over-estimation from segmentation errors |

</details>

---

## Get in touch 🤝

Always glad to hear from people working on quantitative cell biology, image analysis, or the physics of living systems: reach out on [LinkedIn](https://www.linkedin.com/in/alex-papagiannakis-singlecells/) or open an issue on any of the repositories above.

<p align="center">
  <img src="https://github.com/alexSysBio/alexSysBio/blob/main/IMG_8688.jpg?raw=1" alt="" width="50%"/>
  <br>
  <sub>Thanks for visiting 🐬</sub>
</p>
