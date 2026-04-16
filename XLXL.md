# XLXL Engineering Standards

## Core Mandates
- **Language Consistency**: This file (`XLXL.md`) must always be updated and maintained in **English**, regardless of the language used in conversation.
- **Centralized Tasks**: All task-specific directories must be created under `~/xlxl-tasks/`.
- **Session-to-Task Mapping**: Every session corresponds to a single task. A task folder must be initialized at the start of every session.

## Task Management Workflow

1. **Task Directory Creation**: At the beginning of each session, a dedicated folder must be created inside `~/xlxl-tasks/`. The folder name should represent the session's primary objective (e.g., `~/xlxl-tasks/2024-04-15-tmux-setup`).
2. **Progress Tracking (Note.md)**:
    - Each task folder must contain a `Note.md` file.
    - **Findings**: Record all research discoveries, technical challenges, and proposed solutions encountered during the session.
    - **Progress**: Log real-time execution status and key architectural decisions.
3. **Artifact Archiving**: All artifacts, test scripts, and intermediate outputs generated during the session must be stored within that session's task folder.
4. **Verification Standards**: Verification steps and results must be documented in `Note.md` before the session/task is concluded.
