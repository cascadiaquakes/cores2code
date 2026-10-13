# cores2code

[![License: BSD-3-Clause](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](LICENSE)

Welcome to the **cores2code** repository, the digital companion for the final week of the **Cores to Code (C2C)** summer research program. This repository contains instructional materials, datasets, and exercises designed to introduce undergraduate geoscience students to coding and data analysis using Python.

---

**Course book:** https://cascadiaquakes.github.io/cores2code/

---

## About the Program

**Cores to Code** is a three-week immersive summer experience hosted by CRESCENT (the Cascadia Region Earthquake Science Center). The program trains students in subduction zone science through:

- Week 1: **Fieldwork** – Collecting sediment cores from coastal sites
- Week 2: **Lab Analysis** – Stratigraphy, microfossil work, and core interpretation
- Week 3: **Data & Code** – Learning to work with and interpret geologic data using Python (this repo)

---

---

## Week 3 Learning Objectives

During this final week, students transition from physical samples to digital analysis. You'll gain experience in:

- Writing and executing basic Python code
- Loading and cleaning datasets (e.g., from field or lab work)
- Creating figures using `matplotlib` and `plotly`
- Performing simple statistical summaries
- Documenting workflows with Jupyter Notebooks

These skills help bridge traditional geoscience methods with modern computational tools.

---

---

## Repository Structure

```bash
cores2code/
├── notebooks/          # Jupyter notebooks for guided instruction
│   ├── 01_intro_to_python.ipynb
│   ├── 02_data_handling.ipynb
│   ├── 03_plotting_basics.ipynb
│   └── 04_mini_project_template.ipynb
├── data/               # Example datasets (CSV or similar formats)
│   └── sample_cores.csv
├── exercises/          # Hands-on practice notebooks
│   └── 01_data_cleaning_challenge.ipynb
├── requirements.txt    # Python dependencies
└── README.md           # This file
```

---

---

## Getting Started

1. **Install Anaconda** (recommended):  
   [https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution)

2. **Launch Jupyter Lab**:
   ```bash
   jupyter lab
   ```

3. **Install required packages** (if not already installed):
   ```bash
   pip install -r requirements.txt
   ```

4. **Start with the first notebook**:  
   Open `notebooks/01_intro_to_python.ipynb` and follow along.

---

---

## Tools You'll Use

- **Python** – for scripting and analysis
- **Jupyter Notebooks** – for interactive code + narrative
- **NumPy** – for working with arrays and math
- **Pandas** – for data wrangling
- **Matplotlib / Plotly** – for data visualization

---

---

## Attribution & Support

This repository is maintained by instructors and TAs from the **CRESCENT** , with contributions from:
- Cal Poly Humboldt
- University of Oregon
- Virginia Tech
- UNC Wilmington

Contact your instructor or TA if you get stuck or want to go further!

---

---

## Final Notes

This is not about becoming a software engineer—it's about learning how basic coding can help you be a better geoscientist. You'll be analyzing real data, automating repetitive tasks, and visualizing findings. Be curious, experiment, and don’t be afraid to break things (and then fix them)!

Happy coding!

— The C2C Teaching Team

---

## License

This project is licensed under the BSD 3-Clause License. See [LICENSE](LICENSE).

---

## Acknowledgments

<table>
  <tr>
    <td align="center" valign="middle">
      <img src="https://raw.githubusercontent.com/cascadiaquakes/.github/main/assets/crescent-circle.png" alt="CRESCENT Logo" width="150" />
    </td>
    <td align="center" valign="middle">
      <img src="https://raw.githubusercontent.com/cascadiaquakes/.github/main/assets/nsf-logo.png" alt="NSF Logo" width="450" />
    </td>
  </tr>
</table>

This project is supported by the National Science Foundation through the Cascadia Region Earthquake Science Center (CRESCENT), Cooperative Agreement EAR-2225286.
