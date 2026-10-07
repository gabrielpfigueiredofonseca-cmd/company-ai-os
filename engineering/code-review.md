# Code Review

Code review exists to improve correctness, maintainability, security, and shared understanding.

## 1. Review behavior

First determine whether the change actually solves the intended problem.

## 2. Review correctness

Check:

- Logic.
- Edge cases.
- Error handling.
- Data integrity.
- Integration behavior.
- Regression risks.

## 3. Review maintainability

Ask:

- Is the code understandable?
- Is the structure appropriate?
- Is complexity justified?
- Will another developer be able to maintain it?

## 4. Review security

Look for:

- Exposed secrets.
- Unsafe input handling.
- Authorization problems.
- Sensitive data exposure.
- Insecure dependencies.
- Dangerous defaults.

## 5. Review tests

Check whether important behavior is adequately validated.

Ask what could break without being detected.

## 6. Review scope

Look for unrelated changes, unnecessary refactoring, or accidental modifications.

## 7. Review communication

Feedback should be:

- Specific.
- Evidence-based.
- Constructive.
- Focused on the code and its consequences.

## 8. Final review

Before approving, ask:

- Does it solve the problem?
- Is it safe?
- Is it maintainable?
- Is it tested?
- Is anything important missing?
