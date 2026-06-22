---
name: desloppify
description: Scan a project and remove AI slop patterns.
---

Perform a desloppify scan of this project.

Do not make changes yet. Review the codebase and identify:
- rushed or messy implementation
- duplicated logic
- inconsistent naming or structure
- fragile assumptions
- missing error handling
- UI/UX rough edges
- security or validation issues
- dead code or unused files
- places where the architecture is becoming confusing
- anything that works now but will be painful to maintain later

Return a prioritized list:
1. Critical issues
2. Medium cleanup items
3. Nice-to-have polish

For each item, explain:
- where it is
- why it matters
- what you recommend changing
- whether it is safe to fix now or should wait 
