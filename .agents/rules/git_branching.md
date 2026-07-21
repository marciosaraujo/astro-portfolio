# Git Branching Rule

## Objective
Ensure all code modifications are developed in isolated feature branches to protect the integrity of the default branch and follow a clean git workflow.

## Rule Guidelines
- **Always Check Out a Branch First**: Before making any file creations, edits, or commands that modify repository files, you must create a new branch.
- **Naming Convention**: Use descriptive branch names with appropriate prefixes:
  - `feat/` for new features or enhancements (e.g., `feat/custom-visual-style`)
  - `fix/` for bug fixes or corrections
  - `refactor/` for code restructurings
- **No Direct Edits**: Do not make code modifications while checked out on the `main` or default branch.
