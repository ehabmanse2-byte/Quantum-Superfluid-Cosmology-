# Space-time as a Unified Quantum Fluid Model: 3D Computational Simulations & Bayesian MCMC Validation

[![License: MIT](https://shields.io)](https://opensource.org)
[![Python 3.9+](https://shields.io)](https://python.org)

This repository contains the six reproducible numerical simulation notebooks (Python / Jupyter) and Bayesian Markov Chain Monte Carlo (MCMC) parameter estimation scripts accompanying the research paper:

> **Space-time as a Unified Quantum Fluid Model for Dark Components, Quantum Phenomena, and Ordinary Matter: Theoretical Framework, Mathematical Appendix, and Empirical Benchmarks**  
> **Author:** Ehab Mohamed Abdel Gwad Manse (Independent Researcher, Cairo, Egypt)  
> **ORCID:** [0009-0009-4846-6188](https://orcid.org)

---

## Repository Structure & Simulations Overview

All simulations solve the governing differential, stochastic, and Bayesian inference equations derived in **Appendix C** of the manuscript:

| Simulation | Notebook / Script | Physics Domain & Governing Equations | Observational Benchmark |
| :--- | :--- | :--- | :--- |
| **Sim 1** | `Sim1_3D_Hubble_Expansion.ipynb` | 3D Coupled Friedmann–Continuity Expansion ODE $H(z, \rho_{\mathrm{DE}}/\rho_{\mathrm{DM}})$ (Eq. 12) | 31 Cosmic Chronometers & CPL $w(z)$ |
| **Sim 2** | `Sim2_3D_GW_Neutrino_Dispersion.ipynb` | Gravitational wave group-velocity dispersion $v_g(\nu)$ & 3-flavor neutrino density-matrix ODE (Eqs. 9–10) | LIGO GW150914 & IceCube (>35 TeV) |
| **Sim 3** | `Sim3_3D_Macro_Quantum_Loop.ipynb` | 3D Finite-Volume Continuity PDE balancing loop across *The Barzakh* (Eq. 6) | Non-singular mass conservation ($\langle\rho/\rho_{\mathrm{crit}}\rangle = 1$) |
| **Sim 4** | `Sim4_MCMC_DESI_Planck.ipynb` | 60,000-step Metropolis–Hastings Bayesian MCMC parameter estimation ($\beta, \epsilon_{\mathrm{dip}}, \chi_{\mathrm{crit}}$) (Eq. 13) | DESI DR1 BAO & Planck 2018 CMB Dipole |
| **Sim 5** | `Sim5_3D_CERN_Higgs_Fluctuations.ipynb` | Stochastic Ginzburg–Landau Langevin simulation of Higgs mass fluctuations $\Delta m_H(\chi, \gamma)$ (Eq. 7) | CERN ATLAS ($m_H = 125.11 \pm 0.11\,\mathrm{GeV}$) |
| **Sim 6** | `Sim6_3D_EHT_Horizon_Phase_Shear.ipynb` | Relativistic event horizon phase-shear thickness $\Delta R_{\mathrm{horizon}}$ (Eq. 8) | EHT M87* shadow sharpness & Space-VLBI |

---

## Interactive Cloud Execution (Google Colab)

You can run all six notebooks directly in your browser without local installation:

* **Sim 1 (3D Hubble Expansion $H(z)$):** [Open in Colab](https://google.com)
* **Sim 2 (3D GW & Neutrino Dispersion):** [Open in Colab](https://google.com)
* **Sim 3 (3D Macro-Quantum Balancing Loop):** [Open in Colab](https://google.com)
* **Sim 4 (MCMC Bayesian Parameter Estimation):** [Open in Colab](https://google.com)
* **Sim 5 (3D CERN Higgs Mass Fluctuations):** [Open in Colab](https://google.com)
* **Sim 6 (3D EHT Event Horizon Phase Shear):** [Open in Colab](https://google.com)

---

## Local Installation & Usage

To run the notebooks locally, ensure you have Python 3.9+ installed along with the required scientific computing packages:

```bash
pip install numpy scipy matplotlib jupyter
```

Clone the repository and launch Jupyter Notebook:

```bash
git clone https://github.com
cd Unified-Quantum-Fluid-Cosmology
jupyter notebook
```

---

## Citation

If you use these simulation codes or mathematical formulations in your research, please cite this repository and the accompanying paper:

```bibtex
@software{manse2026udf_code,
  author       = {Manse, Ehab Mohamed Abdel Gwad},
  title        = {Space-time as a Unified Quantum Fluid Model: 3D Computational Simulations and Bayesian MCMC Validation},
  year         = {2026},
  publisher    = {Zenodo},
  note         = {Archived on Zenodo; see repository badge for permanent DOI}
}

```
