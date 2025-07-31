# 🧬 _2024_borcsok_ERCC2

This repository contains computational predictions supporting the paper:  
**"Quantitative functional profiling of ERCC2 mutations deciphers cisplatin sensitivity in bladder cancer"**  
by Judit Börcsök, Djavarshini Gopaul, Daphne Devesa-Serrano, Clémence Mooser, Nicolas Jonsson, Matteo Cagiada, Dag R. Stormoen, Maya N. Ataya, Brendan J. Guercio, Hristos Z. Kaimakliotis, Gopa Iyer, Kresten Lindorff-Larsen, Lars Dyrskjøt, Kent W. Mouw, Zoltan Szallasi, and Claus S. Sørensen.  
📄 *[Link to paper – to be added]*

---

## 📚 Contents

This repository includes predictions and analysis files generated using:

- 🧪 **Cagiada Functional Site Model**
- 🧬 **FunC-ESMs annotations** with ClinVar mappings (2023–2024)

---

## 📁 File Structure

- `ercc2_outputs.zip/`
  - `test_residue_predictions.csv`
  - `test_variant_features.csv`
  - `test_variant_predictions.csv`
  - `figures/`
    - `test_GEMME_histogram.png`
    - `test_RaSP_histogram.png`
    - `test_residue_class.png`
    - `test_variant_map.png`
    - `test_WCN_histogram.png`
- `func-esms_P18074-ERCC2_clinvar2023_clinvar2024_mapped.txt`

---

## ⚙️ Methods

### 🧪 Cagiada Functional Site Model

All predictions in `ercc2_outputs.zip` were generated using the model from:

📎 [Google Colab Notebook – Cagiada Functional Site Model](https://colab.research.google.com/github/KULL-Centre/_2022_functional-sites-cagiada/blob/main/Functional_site_model.ipynb)

This model provides residue- and variant-level features including GEMME, RaSP, WCN, and classification outputs.

---

### 🧬 FunC-ESMs Data

The file `func-esms_P18074-ERCC2_clinvar2023_clinvar2024_mapped.txt` was based on data from:  
**"Decoding molecular mechanisms for loss of function variants in the human proteome"**  
by M. Cagiada, N. Jonsson, and K. Lindorff-Larsen (2024, *bioRxiv*).  
📄 [View paper on bioRxiv](https://www.biorxiv.org/content/10.1101/2024.05.21.595203v2)  
💾 [Download dataset via KU ERDA](https://sid.erda.dk/cgi-sid/ls.py?share_id=DUWFpyjZp0)  
➡️ Navigate to `erda/P1/80/74/` to access the specific file used.

Clinical annotations from ClinVar (2023 and 2024) were mapped onto ERCC2 variants in this file for this project.

---

## 📌 Citation

If you use this repository or its data, please cite the associated publication above as well as the tools listed below:

### 🧪 The Cagiada Functional Site Model  
- **Cite this article:**  
  Cagiada, M., Bottaro, S., Lindemose, S. *et al.* _Discovering functionally important sites in proteins_. **Nat Commun** **14**, 4175 (2023).  
  🌐 [https://doi.org/10.1038/s41467-023-39909-0](https://doi.org/10.1038/s41467-023-39909-0)  
- 🧭 This model was used to generate residue- and variant‑level predictions via the [Colab notebook](https://colab.research.google.com/github/KULL-Centre/_2022_functional-sites-cagiada/blob/main/Functional_site_model.ipynb).

---

### 🧬 FunC‑ESMs Dataset & Tools  
- **Cite this article:**  
  Cagiada, M., Jonsson, N., & Lindorff‑Larsen, K. _Decoding molecular mechanisms for loss‑of‑function variants in the human proteome_. **bioRxiv** (2025).  
  🌐 [https://doi.org/10.1101/2024.05.21.595203](https://doi.org/10.1101/2024.05.21.595203)  
- 💾 Data was obtained from the KU ERDA repository. Navigate to **`erda/P1/80/74/`** to download the FunC‑ESMs file used in this project.  
  📎 [ERDA Repository (share link)](https://sid.erda.dk/cgi-sid/ls.py?share_id=DUWFpyjZp0)

Clinical variant annotations from **ClinVar (2023 & 2024)** were mapped into the final `.txt` file (`func‑esms_P18074‑ERCC2_clinvar2023_clinvar2024_mapped.txt`).
