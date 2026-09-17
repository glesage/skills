---
name: plan
description: Make a plan for a coding job
disable-model-invocation: true
---

Create a structured implementation plan for a coding job and save it in a markdown file in the repo.

# Requirements
- Use the job context, attachments and previous chat history to get the most context
- Document everything an engineer with little context needs to know: which files to touch for each task, code, docs they might need to check.

# File Structure
Before defining tasks, map out which files will be created or modified and what each one is responsible for. This is where decomposition decisions get locked in.
- You reason best about code you can hold in context at once, and your edits are more reliable when files are focused. Prefer smaller, focused files over large ones that do too much.
- Files that change together should live together. Split by responsibility, not by technical layer.
- In existing codebases, follow established patterns. If the codebase uses large files, don't unilaterally restructure - but if a file you're modifying has grown unwieldy, including a split in the plan is reasonable.

# Bite-Sized Task Granularity
Each step is one action:
- "Write the failing test" - step
- "Run it to make sure it fails" - step
- "Implement the minimal code to make the test pass" - step
- "Run the tests and make sure they pass" - step
- "Commit" - step

# Guardrails
- Do NOT edit code or mutate other files; output only the structured plan into a markdown file.
