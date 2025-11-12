---
on:
  issues:
    types: [opened]
permissions:
  contents: read
  actions: read
safe-outputs:
  add-comment:
    max: 2
---

# Issue Triage Assistant

When a new issue is created, analyze the issue content and provide helpful guidance.

Examine the issue title and description for:
- Bug reports that need additional information
- Feature requests that should be categorized
- Questions that can be answered immediately
- Issues that might be duplicates

Respond with a helpful comment that guides the user on next steps or provides immediate assistance.