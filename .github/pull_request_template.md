## Description

<!-- Briefly describe what this PR does. 2-3 sentences is usually enough. -->

## Type of Change

<!-- Check the one that applies. -->

- [ ] `feat` - New feature or enhancement
- [ ] `fix` - Bug fix
- [ ] `docs` - Documentation only
- [ ] `refactor` - Code change that neither fixes a bug nor adds a feature
- [ ] `test` - Adding or updating tests
- [ ] `chore` - Maintenance (dependencies, config, etc.)
- [ ] `hot-fix` - Critical production fix

## Related Issues & Requirements

<!-- Link any related GitHub issues or requirement IDs from the FUNCTIONAL_REQUIREMENTS documentation. -->

- Closes #<!-- issue number -->
- Implements: <!-- e.g., FR-CTX-01, FR-ART-05 -->

## Key Changes

<!-- List the key changes made to the code. Use simple bullet points. -->
- 
- 
- 

## How to Test

<!-- Explain any testing scripts, requirements, or commands. Specify the purpose of each type of test. -->
1. 
2. 
3. 

---

## Pre-Review Checklist

<!-- Complete these items before requesting review. Check each box when done. -->

### Code Quality
- [ ] Code generally follows project conventions and style guide
- [ ] Ran `autopep8` to format code
- [ ] Complex variables have type hints
- [ ] Functions have docstrings with Arguments/Returns/Notes sections
- [ ] Any new files are strictly necessary (to avoid bloat)

### Testing
- [ ] Added/updated tests for changes
- [ ] All tests pass locally: `pytest`
- [ ] Test coverage maintained or improved

<!-- Paste test results summary below (optional but helpful) -->

<details>
<summary>Test Results</summary>

```
# Paste pytest output here
```

</details>

### Database (if applicable)
- [ ] Database migration created: `flask db migrate -m "description"`
- [ ] Migration tested: `flask db upgrade` and `flask db downgrade`
- [ ] No destructive changes without team discussion

### Documentation
- [ ] Updated relevant docs if behavior changed
- [ ] Added inline comments for complex logic
- [ ] Comments written with a reviewer audience in mind (not already familiar with the changes)

### Final Checks
- [ ] Branch is up to date with `dev` (or target branch)
- [ ] Commits are atomic and follow format: `type(scope): description`
- [ ] No hardcoded secrets, credentials, or .env files included
- [ ] Reviewed my own diff before requesting review

---

## Screenshots (if applicable)

<!-- Add screenshots for UI changes -->

## Notes for Reviewers

<!-- Anything specific reviewers should look at or be aware of? -->

## Next Steps or TODOs

<!-- Any logical next steps or lingering TODO items. If new issues need to be created for these, link them here. -->


---

**Target Branch:** `dev` | **Reviewer:** @<!-- teammate -->
