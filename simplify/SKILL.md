---
name: simplify
description: Make a plan to refactor code in a branch to be more readable, maintainable and efficient. YAGNI
disable-model-invocation: true
---

Go over all the changes in the branch and look for anything that can be cleaned up, follow YAGNI principles.
Make a plan in a markdown file with your suggestions.

# What to look for
- Code that can be de-duplicated, shared, simplified or refactored to be more readable
- Excessive logs or that that simply state what is already obvious from the code
- Un-exporting functions or variables that are not imported anywhere
- Excessive tests or tests that we useful for development but not critical for the future
