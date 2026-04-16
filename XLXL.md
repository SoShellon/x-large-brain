# XLXL Engineering Standards

## Core Mandates
- **Language Consistency**: This file (`XLXL.md`) must always be updated and maintained in **English**, regardless of the language used in conversation.
- **Centralized Tasks**: All task-specific directories must be created under `~/xlxl-tasks/`.
- **Substantive Task Tracking**: A task folder must be initialized once a session involves substantive research, implementation, or artifact generation. Brief inquiries or surface-level conversations do not require a folder.
- **Explicit Approval for External Changes**: Any action that modifies files, system state, or external resources MUST be approved by the user first. A summary of the proposed changes must be provided for review before execution.
- **Privacy & Secret Prevention**: NEVER push, log, or share secrets, API keys, credentials, or sensitive personal identifiable information (PII) to external repositories or services. Exhaustive checks must be performed before any synchronization.

## Task Management Workflow

1. **Task Directory Creation**: Initialize a dedicated folder inside `~/xlxl-tasks/` when a task reaches the stage of substantive work. The folder name should be concise and descriptive.
2. **Progress Tracking (Note.md)**:
    - Each task folder must contain a `Note.md` file.
    - **Findings**: Record all research discoveries, technical challenges, and proposed solutions.
    - **Progress**: Log real-time execution status and key architectural decisions.
3. **Artifact Archiving**: All artifacts, test scripts, and intermediate outputs generated for the task must be stored within the corresponding task folder.
4. **Verification Standards**: Verification steps and results must be documented in `Note.md` before the task is concluded.

## Change Management
- **Pre-Execution Summary**: Before applying any changes to the codebase or system, provide a concise summary of **what** will change and **why**.
- **User Consent**: Wait for explicit confirmation from the user before proceeding with the implementation.

## Security Protocol
- **Pre-Sync Audit**: Before any `git push` or external data transfer, scan for sensitive patterns (e.g., `.env` files, `id_rsa`, hardcoded keys).
- **Sanitization**: Any session notes or artifacts intended for the `xlxl-standards` repo must be reviewed for inadvertent disclosure of private information.
