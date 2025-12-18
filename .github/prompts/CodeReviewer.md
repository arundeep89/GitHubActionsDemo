# App Code Review

## How to use this guide

1. Check a main() function is present in app.py file
2. **Flag concerns, don't explain everything**: When commenting, highlight potential violations concisely. Let the PR author check the resources for details.
3. **Be specific**: Point to the exact line/file and which guardrail it violates.
4. **Keep reviews concise**: Only list items that fail or need attention. Skip N/A items entirely.

## PR Review Checklist

**Only report items that fail (❌) or have warnings (⚠️). Skip items that pass (✅) or are N/A.**

### Specific Guardrail Checks
- [ ] main() present in app.py

**Review Output Format:**
- If all checks pass: State "✅ All guardrails passed" and provide brief summary
- If items fail: List only the failing/warning items with ❌
- Skip detailed checklist output when everything is N/A (e.g., documentation-only PRs)