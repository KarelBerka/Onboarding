# Blogging Exercise 2: Code & Computational Tasks

* **Goal:** Gain confidence running, documenting, and explaining a piece of scientific code.
* **Timeline:** Within your first three weeks of joining the lab.
* **Format:** A Jupyter notebook or a short Markdown guide (approx. 500 words) detailing a computational script or workflow.

---

## The Brief
In the Chemical Data Lab, we write code to analyze structures, query chemical databases, and run molecular simulations. The brief for this exercise is to **get a specific script or library running, test it on a sample dataset, and write a tutorial-style explanation of how it works.**

Your target audience is a new student who has never used this tool before. Focus on what was tricky, how you solved it, and what the code achieves.

### Suggested Coding Projects
1. **MolMeDB API Query (Cheminformatics):**
   * Write a Python script to query the MolMeDB REST API for a set of compounds (e.g., caffeine, ibuprofen).
   * Retrieve their membrane partition coefficients ($K_{ow}$) and plot them using `matplotlib` or `seaborn`.
2. **RDKit Property Calculator (Cheminformatics):**
   * Use the RDKit library in a Jupyter notebook to read a list of SMILES strings.
   * Calculate chemical descriptors (e.g., Lipinski's Rule of 5 properties, polar surface area) and render their 2D chemical structures.
3. **PyMOL Structure Analysis (Structural Bioinformatics):**
   * Write a short PyMOL script (`.pml` or python script) to load a cytochrome P450 structure from the PDB.
   * Highlight its heme group, locate the active site, and measure the distance between the iron atom and a bound ligand.
4. **Simulation Trajectory Parser (Molecular Dynamics):**
   * Write a script using `MDAnalysis` or `MDTraj` to read a GROMACS trajectory (`.xtc` / `.gro` files) and calculate the root-mean-square deviation (RMSD) over time.

---

## Key Questions to Answer in Your Write-Up
* **Why:** What is the purpose of this script, and how does it support our research?
* **Setup:** What packages and dependencies did you need to install (e.g., using `pip`, `conda`, or `uv`)?
* **Execution:** Show a step-by-step example with input code and output data/plots.
* **Takeaway:** What did you learn, and how can this script be reused in the future?

---

## How to Submit
Upload your Jupyter notebook or markdown file to your directory in `meetings/your-name/` and push it to GitHub, or share it in MS Teams.
