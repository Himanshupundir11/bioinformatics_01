
# 🔬 Simulated Bioinformatics Pipeline

This repository contains a complete **bioinformatics pipeline** built on a randomly generated gene expression dataset. It simulates a disease-vs-control transcriptomic study, using only Python for statistical and visual analysis.

---

## 📁 Files

| File Name                               | Description                                                  |
|----------------------------------------|--------------------------------------------------------------|
| `simulated_gene_expression.csv`        | Simulated gene expression data for 1000 genes across 20 samples |
| `Bioinformatics_Pipeline_Simulated.ipynb` | Full Jupyter notebook pipeline                               |
| `results_differential_expression.csv`  | Output of statistical test results (DEGs)                    |

---

## 🧬 Pipeline Steps

1. **Data Generation**
   - Simulate expression profiles for control and disease groups.

2. **Differential Expression**
   - T-tests across conditions
   - Volcano plot visualization

3. **Dimensionality Reduction**
   - PCA and t-SNE for high-dimensional data compression

4. **Clustering**
   - Heatmap of top DEGs using hierarchical clustering

5. **Simulated Pathway Enrichment**
   - Random pathway assignment to genes for illustrative enrichment plot

---

## 🛠 Technologies Used

- Python 3
- NumPy, Pandas
- SciPy, scikit-learn
- Seaborn, Matplotlib

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/yourusername/bioinformatics-pipeline-simulated.git
cd bioinformatics-pipeline-simulated

# (Optional) Create virtual environment
python -m venv env
source env/bin/activate  # Windows: .\\env\\Scripts\\activate

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Bioinformatics_Pipeline_Simulated.ipynb
