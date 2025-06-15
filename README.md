# 🧬 Dog Gene-Phenotype Visualization Project

> Explore and visualize the complex relationships between canine genotypes and observable phenotypes using graph-based insights and bioinformatics techniques.

---

## 📚 Table of Contents

- [📌 Overview](#-overview)
- [✨ Key Features](#-key-features)
- [💡 Novelty & Innovation](#-novelty--innovation)
- [🔬 Methodology](#-methodology)
- [📈 Progress](#-progress)
- [📊 Results & Findings](#-results--findings)
- [🚀 Future Scope](#-future-scope)
- [🛠️ Tech Stack](#-tech-stack)
- [👩‍💻 Author](#-author)
- [📄 License](#-license)
- [🤝 Contributing](#-contributing)
- [🔝 Back to Top](#-table-of-contents)

---

## 📌 Overview

This project focuses on **visualizing genetic traits in dogs** and mapping them to physical and behavioral phenotypes. Using curated datasets and graph/network-based tools, we aim to uncover patterns in how genes influence traits like coat color, behavior, health risks, and more.

The project is designed to help breeders, researchers, and pet enthusiasts **understand the genetic foundations of canine traits** in an interactive, visual, and scientific way.

---

## ✨ Key Features

- 🧠 Maps dog genes to traits like size, color, behavior, and health
- 🌐 Builds gene-phenotype bipartite graphs for visualization
- 🧩 Detects clusters of related traits or genes
- 🎯 Calculates importance/centrality of specific genes
- 📊 Interactive visualizations (with PyVis / Plotly / Dash)
- 🧬 Data sourced from real-world veterinary genetics databases

---

## 💡 Novelty & Innovation

- ✅ **Domain-Specific Visualizations:** Tailored graphs to represent biological mappings between genotype and phenotype
- ✅ **Bipartite & Projected Networks:** Enables both gene-trait and trait-trait network perspectives
- ✅ **Interactive Exploration:** Visual network browser to explore relationships
- ✅ **Research-Ready Pipeline:** Easily extendable for new breeds, traits, or comparative species

---

## 🔬 Methodology

1. **Data Collection & Cleaning**
   - Curated gene-trait pairs from open-access animal genetic databases
   - Removed inconsistencies, normalized trait and gene names

2. **Graph Construction**
   - Built bipartite graph (genes ↔ traits)
   - Projected graph: trait-to-trait and gene-to-gene similarity

3. **Analysis**
   - Degree centrality, clustering coefficients, community detection
   - Identified influential genes and co-expressed traits

4. **Visualization**
   - PyVis, Plotly, and NetworkX visualizations
   - Interactive Jupyter + HTML network explorer

---

## 📈 Progress

| Module                     | Status      |
|---------------------------|-------------|
| Data Ingestion & Cleaning | ✅ Completed |
| Bipartite Graph Building  | ✅ Completed |
| Trait-Gene Mapping        | ✅ Completed |
| Visualization             | ✅ Completed |
| Report & Notebook         | ✅ Completed |

---

## 📊 Results & Findings

- 🎯 Identified **key genes** responsible for clusters of traits (e.g., coat + eye color genes)
- 🧠 Found high centrality genes involved in **neurological and behavioral traits**
- 🧬 Traits such as "aggressiveness" and "shedding" often shared **common genetic markers**
- 📌 Built interpretable networks for easy use by dog breeders and vet researchers

> 📎 *Full results and visuals are available in [`DogGenePhene_Analysis.ipynb`](./DogGenePhene_Analysis.ipynb) and [`report.pdf`](./report.pdf).*
     --coming soon

---

## 🚀 Future Scope

- 🧪 Add support for **multi-species comparison** (e.g., cats, wolves)
- 🌱 Integrate with **machine learning models** for trait prediction
- 🧬 Accept user input: Upload genetic test data to view trait predictions
- 📦 Package as a pip-installable or web-hosted tool (e.g., Streamlit)

---

## 🛠️ Tech Stack

| Tool/Library | Purpose                            |
|--------------|------------------------------------|
| Python 3.8+  | Core scripting and data handling   |
| pandas       | Data manipulation                  |
| networkx     | Graph creation and analysis        |
| matplotlib   | Static visualizations              |
| pyvis        | Interactive network graphs         |
| plotly       | Optional interactive dashboards    |
| jupyter      | Notebooks for exploration & reports|

---

## 👩‍💻 Author

Made with 🐾 and 💻 by  
**[Latha Easwaramurthy](https://github.com/im-kozhandha)**  
> Let’s connect! Reach out for collaborations or ideas.

---

## 📄 License

This project is licensed under the **MIT License**.  
See the [LICENSE](./LICENSE) file for details.

---

## 🤝 Contributing

Contributions welcome!

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -m 'Add feature'`
4. Push to your branch: `git push origin feature-name`
5. Create a Pull Request

---

## 🔝 [Back to Top](#-table-of-contents)
