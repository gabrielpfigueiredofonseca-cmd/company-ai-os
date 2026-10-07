# Testing

Testing exists to provide evidence that software behaves as intended.

## 1. Test important behavior

Prioritize tests around:

- Core business logic.
- Critical user flows.
- Data integrity.
- Authentication and authorization.
- Important integrations.
- High-risk edge cases.

## 2. Test before declaring completion

Important changes should be validated before being considered complete.

Validation may include:

- Automated tests.
- Manual verification.
- Integration tests.
- Type checking.
- Linting.
- Build verification.
- Security checks.

Use the methods appropriate to the project.

## 3. Test behavior, not implementation details

Tests should primarily verify what the system should do.

Avoid tests that become fragile because they depend unnecessarily on internal implementation details.

## 4. Edge cases

Consider:

- Empty inputs.
- Invalid inputs.
- Missing data.
- Unexpected data.
- Boundary values.
- Permission failures.
- Network failures.
- Duplicate operations.
- Partial failures.

## 5. Regression prevention

When a bug is discovered, consider creating a test that would prevent the same bug from returning.

## 6. Test quality

A test should be:

- Reliable.
- Understandable.
- Repeatable.
- Relevant.
- Fast enough for its purpose.

Avoid tests that pass without meaningfully validating behavior.

## 7. Before delivery

Ask:

- What changed?
- What could have broken?
- What tests cover the change?
- What remains untested?
- What evidence supports that the implementation works?
