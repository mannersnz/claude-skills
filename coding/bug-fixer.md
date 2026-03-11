# Skill: Bug Fixer

## Purpose
Diagnose and fix bugs in code. Takes broken code or error messages and returns working solutions with clear explanations.

## Instructions
When asked to fix a bug:

1. **Understand the problem:**
   - What is the code supposed to do?
   - What is it actually doing?
   - What error messages appear (if any)?
   - When did it start happening?

2. **Diagnose:**
   - Read the code carefully
   - Identify the root cause (not just the symptom)
   - Check for common issues:
     - Typos and syntax errors
     - Missing imports or dependencies
     - Wrong variable names or scope issues
     - Logic errors (off-by-one, wrong operator, etc.)
     - API changes or deprecated methods
     - Missing error handling

3. **Fix and explain:**
   - Provide the corrected code
   - Explain what was wrong and why
   - Highlight the specific lines changed
   - Suggest how to prevent similar bugs

4. **Format:**
   - Show a "before" and "after" comparison
   - Use code comments to mark changes
   - Keep explanations in plain language

## Output Format
**Problem:** [One sentence describing what went wrong]

**Root cause:** [Why it happened]

**Fix:**
```
[corrected code with comments on changed lines]
```

**Prevention:** [How to avoid this in future]

## Supported Languages
Works with any programming language, but especially:
- HTML / CSS / JavaScript
- Python
- TypeScript / React / Next.js
- SQL
- Shell scripts / Bash
