# Hi, I'm Yongbeom Kim 👋

### Metrology × AI × Uncertainty Quantification

Optics Ph.D. with 8+ years in optical & semiconductor metrology (SEM, AFM, Raman, NSOM),
building AI applications that don't just predict — they report **how much you can trust
the prediction**, with GUM-compliant uncertainty budgets (JCGM 100/101).

- 🔬 **Measurement scientist first**: ISO 18516 round-robin lead contributor · KOLAS-accredited calibration & testing background
- 📐 I build the full loop: **physics forward model → inverse solver → GUM uncertainty budget**
- 🧰 Domains: OCD / scatterometry, XRR, SEM·TEM image analysis, AFM probe health, Raman/SERS QC
- 🤖 MCP builder: author of the first Model Context Protocol server for GUM measurement uncertainty

## 🚀 Featured Projects

| Project | What it does | Stack |
|---|---|---|
| [metrology-inverse](https://github.com/kyb8801/metrology-inverse) | Forward → inverse → **GUM uncertainty** across 3 instruments: OCD (RCWA), XRR (Parratt), autodiff CD fitting — validated on real **NIST scatterometry data** (L100P300, 9 dies). Exact-Jacobian sensitivity for the uncertainty budget. | Python, PyTorch, Meent, refnx |
| [measurement-uncertainty-mcp](https://github.com/kyb8801/measurement-uncertainty-mcp) | First MCP server for **GUM-compliant uncertainty analysis**: Type A/B, Welch–Satterthwaite ν_eff, expanded U(k), JCGM 101 Monte Carlo, KOLAS-ready budgets. | Python, MCP |
| [tiphealth](https://github.com/kyb8801/tiphealth) | Recipe-aware **HAR AFM tip predictive maintenance** — hybrid Archard physics + ML, 8 industrial probes × 6 materials, NIST-calibrated wear rates, conformal prediction intervals, Dockerized API. | Python, Docker, Streamlit |
| [spectraguard](https://github.com/kyb8801/spectraguard) | Uncertainty-aware **spectral QC** for SERS/Raman/IR — 6-metric confidence score with bootstrap CIs, cross-instrument transfer, streaming SPC, CLI + CI pipeline. | Python, NumPy, SciPy |
| [semiconductor-defect-classifier](https://github.com/kyb8801/semiconductor-defect-classifier) | Defect classification on **SECOM fab sensor data** (1,567 wafers × 590 sensors, 6.6% defect rate) — imbalance handling, Optuna tuning, honest K-fold evaluation. | Python, XGBoost, Optuna |
| [semiconductor-ai-portfolio](https://github.com/kyb8801/semiconductor-ai-portfolio) | Analysis pipelines on **my own PhD measurement data**: MoSe₂ photoluminescence peak/FWHM analysis, NSOM defect mapping, TMD comparison. | Jupyter, pandas, SciPy |

## 🔌 MCP & Open Source

Model Context Protocol servers I built and maintain:

- **[measurement-uncertainty-mcp](https://github.com/kyb8801/measurement-uncertainty-mcp)** — 10 GUM/JCGM tools for ISO/IEC 17025 calibration labs, from any MCP client
- **[vertical-mcp](https://github.com/vertical-mcp)** org — Korean government open-data connectors: [dart-mcp](https://github.com/vertical-mcp/dart-mcp) (corporate disclosures, OpenDART) · [kolas-mcp](https://github.com/vertical-mcp/kolas-mcp) (ISO/IEC 17025 accredited-lab registry) · [ntis-mcp](https://github.com/vertical-mcp/ntis-mcp) (national R&D projects & funding) · [grant-mcp](https://github.com/vertical-mcp/grant-mcp) (NSF / ERC / NRF grant search)
- **[schedule-optimizer-mcp](https://github.com/kyb8801/schedule-optimizer-mcp)** · **[notion-workspace-automation-mcp](https://github.com/kyb8801/notion-workspace-automation-mcp)** — productivity MCP servers

## 🛠️ Tech

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat)
![Optuna](https://img.shields.io/badge/Optuna-4B77BE?style=flat)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**Metrology & standards:** GUM (JCGM 100:2008) · JCGM 101 Monte Carlo · ISO/IEC 17025 · RCWA · XRR · SEM/TEM · AFM · Raman/SERS · NSOM

## 📫 Contact

- 📧 kyb8801@gmail.com
- 🌐 https://yongbeom.com
