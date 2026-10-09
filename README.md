# AST 208 — Astronomy Data Labs

![Python](https://img.shields.io/badge/python-3.9%2B-blue) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

Lab notebooks analyzing astronomical data with Python: measuring distances with parallax, the proper motion of an asteroid, and calibrating CCD images into a three-color composite of the Crab Nebula (M1). Labs were completed in small teams; collaborators are listed in each notebook.

**Course:** AST 208  
**Term:** Spring 2023  
**Institution:** Michigan State University

## Notebook Index

### Labs

- [`lab02_parallax.ipynb`](labs/lab02_parallax.ipynb) — Lab 2: Measuring Sizes and Distances from Angles (71 Total Points)
- [`lab04_proper_motion.ipynb`](labs/lab04_proper_motion.ipynb) — Lab 4: Measuring the Proper Motion of an Asteroid
- [`lab06_three_color_image.ipynb`](labs/lab06_three_color_image.ipynb) — AST 208 Lab 6: Three-Color Image

## Repository Structure

```text
ast208-astronomy-labs/
├── labs/
│   ├── lab02_parallax.ipynb
│   ├── lab04_proper_motion.ipynb
│   └── lab06_three_color_image.ipynb
├── LICENSE
├── README.md
└── requirements.txt
```

## Tech Stack

Python, NumPy, Astropy, matplotlib

## Getting Started

```bash
git clone https://github.com/siddakmarwaha/ast208-astronomy-labs.git
cd ast208-astronomy-labs
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

> **Academic integrity:** This repository contains my own submitted work for a university course and is shared as a portfolio sample. Assignment prompts and starter code belong to the course instructors. Current students should not copy this work.

## Author

**Siddak Marwaha**

## License

Code in this repository is released under the [MIT License](LICENSE). Course-provided prompts and materials remain the property of their authors.
