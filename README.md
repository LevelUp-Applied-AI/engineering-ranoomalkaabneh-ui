[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/g7vj6YXc)
# AI.SPIRE Pre-Work — Phase 3: Engineering Practices

**GitHub Classroom Phase 3 repo.** Days 6–9.

Phase 3 covers PR hygiene, pytest, SQL, and Docker — the engineering practices that make code reviewable, testable, and deployable.

---

## Phase overview

| Day | PR | Topic |
|-----|----|-------|
| 6 | PR 5 | PR Hygiene: Template + Self-Review Checklist |
| 7 | PR 6 | First Tests: Make 5 Failing Tests Pass |
| 8 | PR 7 | SQLite Queries |
| 9 | PR 8 | Docker + Postgres Container Validation |

---

## Setup

Your venv and all packages from `requirements-prework.txt` should already be installed from Day 3. If you need to reinstall:

```bash
python -m venv .venv
source .venv/bin/activate   # Mac/Linux
# or: source .venv/Scripts/activate  (Windows Git Bash)
pip install -r requirements-prework.txt
```
## How to run

Follow these steps to run the project locally:

1. Set up the environment:
   - Open a terminal in the project root directory.
   - Activate the virtual environment:
     - Windows: `.venv\Scripts\activate`
   - Install dependencies:
     ```
     pip install -r requirements-prework.txt
     ```

2. Run the project:
   - Make sure you are in the root directory of the repository.
   - Run the appropriate command (for example, running tests):
     ```
     pytest
     ```

3. Confirm success:
   - All tests should pass without errors.
   - You should see a summary showing that tests completed successfully.