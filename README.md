 Protein-RNA Interface Analysis

This repository provides a Python-based workflow to identify interface residues and nucleotides in binary protein-RNA complexes based on accessible surface area (ASA) data from NACCESS. The analysis includes:

✔ Counting interface atoms in protein, RNA, and complex.
✔ Identifying interface residues & nucleotides in protein & RNA.
✔ Calculating the total interface area for protein, RNA, and complex.
✔ Visualizing interface residues as spheres using PyMOL.

🚀 Features
🔹 Reads NACCESS ASA output files for protein, RNA, and complex.
🔹 Identifies interface atoms and residues based on ASA differences.
🔹 Calculates total interface area in Å².
🔹 Generates CSV output files for further analysis.
🔹 Creates a PyMOL script to visualize interface residues.

📂 Repository Structure
Copy
Edit
📦 protein-rna-interface-analysis
 ┣ 📂 data               # Input ASA and PDB files  
 ┣ 📂 scripts            # Python analysis & PyMOL visualization  
 ┣ 📄 README.md          # Documentation  
 ┣ 📄 requirements.txt   # Python dependencies  
 ┣ 📄 LICENSE            # Open-source license  
 ┗ 📄 .gitignore         # Ignore unnecessary files  
🛠 Installation & Usage
1️⃣ Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
2️⃣ Run the analysis:

bash
Copy
Edit
python scripts/analyze_interface.py
3️⃣ Visualize interface residues in PyMOL:

bash
Copy
Edit
pymol scripts/visualize_interface.pml
📜 License
🔹 Open-source under the Personal License.
💡 Contributions Welcome! Fork the repo, submit pull requests, or report issues. 🚀


