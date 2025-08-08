## 🌳 Branching Strategy

This project uses the Git Flow model for version control.

* **`main`**: This branch contains production-ready code. It is only updated by merging from the `dev` branch for a new release and is tagged with version numbers (e.g., `v1.0.0`).
* **`dev`**: This is the primary development branch. All feature branches are merged into `dev`.
* **`feature/*`**: All new work is done on a feature branch, which branches off from `dev`. For example, `feature/add-new-button`.
