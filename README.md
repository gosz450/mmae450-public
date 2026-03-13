
<p align="center">
  <img src="assets/beam_problem.png" width="48%">
  <img src="assets/pinn_architecture.png" width="48%">
</p>

<h1 align="center">MMAE 450 — Computational Mechanics</h1>

<p align="center">
Finite difference methods, balance laws, and physics-informed neural networks.
</p>


This repository contains the official computational materials for  
**MMAE 450: Computational Mechanics II**.

The course builds directly on **MMAE 350** and extends those ideas to
engineering systems governed by **partial differential equations (PDEs)**,
advanced numerical methods, and modern data-driven modeling approaches.

This repository is organized to support a **reproducible, notebook-driven
computational workflow**, consistent with professional engineering practice.

---

## 📘 Course Context

MMAE 450 emphasizes the connection between:

- physical modeling assumptions  
- governing equations (balance laws and PDEs)  
- numerical discretization (FDM, FVM, FEM)  
- stability, accuracy, and convergence analysis  
- interpretation of computational results  

Later modules introduce **regression, classification, and physics-informed
neural networks (PINNs)** as complementary tools for prediction and surrogate
modeling.

Programming is treated as a *means to support modeling and reasoning*, not
as an end in itself.

---

## 🗂 Repository Organization

The repository mirrors the structure used in **MMAE 350**, with materials
organized by **module**.

At the top level:

```text
mmae450/
├── modules/        # Core instructional content by module
├── homework/       # Homework notebooks and submissions
├── syllabus/       # Course syllabus (PDF)
├── tex/            # LaTeX sources for slides, figures, and assignments
├── tools/          # Utility scripts and supporting resources
└── README.md
```

---

## 📦 Modules

All instructional content lives in the `modules/` directory.

Each module typically contains:

- `notebooks/` — Jupyter notebooks used in lecture, demos, or assignments  
- `slides/` — Lecture slides (PDF)  
- `README.md` — A short overview of the module’s goals and contents  

Example:

```text
modules/
├── module02_newtons_method_nonlinear_systems/
│   ├── notebooks/
│   ├── slides/
│   └── README.md
```

Modules are released progressively during the semester and may be updated
to correct errors, clarify explanations, or extend examples.

Students are expected to **pull updates regularly**.

---

## 📓 Notebooks

Jupyter notebooks are the primary computational medium for this course.

They are used to:

- implement numerical algorithms  
- explore stability and convergence behavior  
- verify computational results  
- connect numerical output to physical interpretation  

Unless explicitly stated otherwise, **submitted notebooks must run from
top to bottom without modification** in a clean environment.

---

## 🧪 Computational Environment

All work in MMAE 450 uses **Python**.

Required libraries include (but are not limited to):

- NumPy  
- SciPy  
- SymPy  
- Matplotlib  
- scikit-learn  
- PyTorch (for selected modules)

As in MMAE 350, students are expected to work in a **local Python virtual
environment** to ensure reproducibility and consistency.

Setup instructions are provided in:

```text
modules/module00_setup/
```

---

## 📝 Homework

Homework assignments emphasize:

- numerical implementation  
- modeling choices and assumptions  
- interpretation of results  
- clarity of communication  

Homework materials are distributed through the `homework/` directory and
via Canvas.

Collaboration at the level of discussion and approach is encouraged, but
all submitted work must be your own.

---

## ☁️ Advanced & Cloud-Based Workflows

Selected modules and the final project may involve:

- larger computational studies  
- data-driven models  
- cloud-based execution or deployment  

These topics build directly on the numerical foundations developed earlier
in the course and will be introduced incrementally.

---

## 📚 Primary Reference

**Computational Mechanics: A Modern Introduction with Machine Learning and AWS Workflows**  
Michael Gosz  

This repository serves as the computational companion to the textbook.

---

## ⚠️ Academic Integrity

All work must comply with Illinois Tech’s academic integrity policies.

Copying code or solutions from other students or online sources without
proper attribution is not permitted.

When in doubt, ask.

---

## ✅ Final Notes

Think of this repository as a **professional engineering workspace**:

- keep your work organized  
- document your reasoning  
- verify your results  
- question whether the output makes physical sense  

Computational mechanics is not about getting numbers —  
it is about understanding *what those numbers mean*.

Welcome to MMAE 450.
