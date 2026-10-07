# Coding Standards

These standards define how the AI should write and maintain software.

## 1. Understand before coding

Before changing code:

- Understand the objective.
- Inspect the existing code.
- Identify dependencies.
- Understand the current architecture.
- Avoid changing code that is not necessary.

Do not write code before understanding the problem.

## 2. Prefer simple solutions

Prefer code that is:

- Simple.
- Readable.
- Maintainable.
- Testable.
- Predictable.

Avoid unnecessary abstractions, frameworks, dependencies, and complexity.

## 3. Readability

Code should be understandable by another developer.

Prefer:

- Clear names.
- Small functions.
- Logical organization.
- Consistent structure.
- Explicit behavior.

Avoid clever code when simple code is possible.

## 4. Separation of responsibilities

Each component should have a clear responsibility.

Avoid creating large functions, classes, or modules that do many unrelated things.

## 5. Error handling

Errors should be handled intentionally.

The AI should:

- Validate important inputs.
- Handle expected failures.
- Avoid silently ignoring errors.
- Provide useful error information.
- Avoid exposing sensitive information.

## 6. Security

Security must be considered during development.

Never:

- Hardcode secrets.
- Expose credentials.
- Disable security controls without justification.
- Trust unvalidated external input.
- Commit sensitive information to the repository.

## 7. Dependencies

Before adding a dependency, consider:

- Whether it is actually necessary.
- Maintenance status.
- Security.
- License.
- Project compatibility.
- Long-term cost.

Prefer existing project capabilities when they are sufficient.

## 8. Changes

Keep changes focused.

A change should solve a defined problem without unnecessarily modifying unrelated parts of the system.

## 9. Documentation

Document important decisions, non-obvious behavior, public interfaces, and architectural constraints.

Do not write documentation that merely repeats obvious code.

## 10. Quality standard

Before considering code complete, verify:

- It solves the intended problem.
- Existing functionality still works.
- Important edge cases were considered.
- Tests were created or updated when appropriate.
- Security implications were considered.
- The code is understandable.
