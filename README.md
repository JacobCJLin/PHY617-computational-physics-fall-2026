# PHY 517/617: Computational Physics (Fall 2026)
## Classical Simulation Methods for Quantum Mechanics

University of Miami — Prof. Cheng-Ju Lin (Jacob), `cxl2103 at umiami.edu`

Course materials for PHY 517/617: exact diagonalization, matrix product states,
and Heisenberg-picture / Pauli propagation. See [syllabus.md](syllabus.md) for
logistics, grading, and the AI policy.

## Layout

- `NB*.ipynb` — in-class notebooks. Bring your laptop; we work these during lecture.
- `HW*.ipynb` — homework notebooks, applying the algorithms to physics problems.
- `00_qm_linalg_review.ipynb` — quantum mechanics / linear algebra refresher.

Materials are posted as the semester progresses, so pull before each class:

```bash
git pull
```

Solution notebooks are posted after the corresponding due date.

## Setup

This repository uses [uv](https://docs.astral.sh/uv/) for environment management:

```bash
uv sync
uv run jupyter lab
```
