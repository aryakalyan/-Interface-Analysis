# Protein-RNA Interface Analysis

This repository provides a Python-based workflow to identify interface residues and nucleotides in binary protein-RNA complexes based on accessible surface area (ASA) data from NACCESS. The analysis includes:

✔ Counting interface atoms in protein, RNA, and complex.  
✔ Identifying interface residues & nucleotides in protein & RNA.  
✔ Calculating the total interface area for protein, RNA, and complex.  
✔ Visualizing interface residues as spheres using PyMOL.

## 🚀 Features

🔹 Reads NACCESS ASA output files for protein, RNA, and complex.  
🔹 Identifies interface atoms and residues based on ASA differences.  
🔹 Calculates total interface area in Å².  
🔹 Generates CSV output files for further analysis.  
🔹 Creates a PyMOL script to visualize interface residues.

## 📂 Repository Structure

📦 protein-rna-interface-analysis
 ┣ 📂 data
 ┃ ┣ 📄 protein.asa
 ┃ ┣ 📄 rna.asa
 ┃ ┣ 📄 complex.asa
 ┃ ┗ 📄 example.pdb
 ┣ 📂 scripts
 ┃ ┣ 📄 analyze_interface.py
 ┃ ┗ 📄 visualize_interface.pml
 ┣ 📄 requirements.txt
 ┣ 📄 README.md
 ┣ 📄 LICENSE
 ┗ 📄 .gitignore


## 🛠 Installation & Usage

1️⃣ **Install dependencies**:

```bash
pip install -r requirements.txt
2️⃣ Run the analysis:

python scripts/analyze_interface.py
3️⃣ Visualize interface residues in PyMOL:

pymol scripts/visualize_interface.pml

📜 License
🔹 This project is privately licensed. Unauthorized use, copying, or distribution is strictly prohibited.
For inquiries regarding permissions, please contact arya.dhokte@gmail.com.

💡 Contributions Welcome! Fork the repo, submit pull requests, or report issues. 🚀
