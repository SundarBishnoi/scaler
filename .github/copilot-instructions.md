# Copilot Instructions for Scaler Workspace

## Overview
This workspace appears to be organized for a curriculum or course structure, with modules and documentation separated by topic. There are no code files or explicit build/test workflows present yet. The following conventions and structure should guide AI coding agents:

## Directory Structure
- `101/` and `Docs/`: Contain reference documents, guides, and personal documents. Not for code.
- `Modules/`: Main location for code and curriculum content. Each subfolder (e.g., `m1_python/`, `m2_problem_solving/`) represents a module or topic. These are currently empty and ready for new content.

## Patterns and Conventions
- **Module Organization:** Place all code, exercises, and supporting files for a topic inside its respective `Modules/<module_name>/` folder.
- **Documentation:** Store supporting documents in `Docs/` or the root. Do not mix code and documentation in the same folder.
- **Naming:** Use descriptive, lowercase, and underscore-separated names for new files and folders (e.g., `data_structures.py`, `lesson_01.md`).
- **No Detected Build/Test Workflow:** If adding code, include a `README.md` in each module to describe its purpose and usage. Add test scripts or instructions as needed.

## Guidance for AI Agents
- When generating new code, always place it in the appropriate `Modules/<module_name>/` directory.
- If creating new modules, follow the existing naming pattern (`m<number>_<topic>`).
- If introducing a build or test workflow, document it clearly in a `README.md` at the module or root level.
- Do not modify or place code in `Docs/` or `101/`.
- Reference or link to key documents in `Docs/` if needed for context.

## Example
To add a Python exercise for problem solving:
1. Create `Modules/m2_problem_solving/exercise_01.py`.
2. Add a brief description in `Modules/m2_problem_solving/README.md`.

---

_If this structure changes or new workflows are introduced, update these instructions to keep AI agents productive._
