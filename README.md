# 🧬 ChemADMET  Compound Properties Analysis Platform

A lightweight, single-file web app for looking up chemical compounds and exploring their **ADMET** (Absorption, Distribution, Metabolism, Excretion, Toxicity) properties  built with plain HTML, CSS, and JavaScript, powered by the **PubChem API**.

## 🔍 Features

- **Compound Search**  search by name with live, debounced autocomplete suggestions pulled from PubChem
- **ADMET Property Dashboard** visualizes absorption, distribution, metabolism, and excretion characteristics with score bars
- **Toxicity Predictions**  rule-based mutagenicity, carcinogenicity, and overall risk-level estimation from structural alerts (e.g. halogens, nitro groups, aromatic ring count, molecular weight)
- **Mobile-first UI**  responsive, app-style layout with tabbed navigation (Home / ADMET / Toxicity / Help / About)
- **External resource links**  quick access to specialized tools like ProTox-II and ADMETmesh for deeper validation

## 🛠️ Tech Stack

- Vanilla **HTML / CSS / JavaScript** — no frameworks, no build step
- **PubChem PUG REST API** for compound data
- CSS custom properties (design tokens) for theming

## 🚀 Getting Started

No installation needed  it's a single static file.

1. Clone the repo:
   ```bash
   git clone https://github.com/Vikram1014/chemADMET.git
   ```
2. Open `index.html` in any browser, or serve it locally:
   ```bash
   npx serve .
   ```

**Live demo:** _add your GitHub Pages link here once enabled_ (Settings → Pages → main branch → root)

## ⚠️ Disclaimer

Toxicity and ADMET predictions in this tool are **computational estimates** based on simplified structural rules. They are intended for educational/exploratory purposes only and should always be validated against experimental toxicology data and regulatory guidelines before any real-world safety decision.

## 📌 Roadmap Ideas

- Replace rule-based toxicity logic with a trained ML model
- Add molecule structure rendering (2D/3D)
- Export results as PDF/CSV
- Batch compound comparison

## 📄 License

MIT — feel free to use and adapt.

## 👤 Author

**Vikram S**
📍 Coimbatore
🔗 [LinkedIn](https://linkedin.com/in/vikram1014)
🔗 [GitHub](https://github.com/Vikram1014)
