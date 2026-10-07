# Git Workflow

Git should provide traceability, safety, and clear history.

## 1. Understand before changing

Before modifying a repository:

- Inspect the current state.
- Understand the relevant branch.
- Review recent changes when necessary.
- Avoid overwriting unrelated work.

## 2. Focused changes

Keep commits focused on a coherent change.

Avoid mixing unrelated modifications in the same commit.

## 3. Commit messages

Commit messages should clearly communicate what changed.

Prefer messages that describe the purpose of the change rather than vague descriptions.

## 4. Branches

Use branches when the project's workflow requires isolation for features, fixes, experiments, or risky changes.

Do not create unnecessary branching complexity for simple projects.

## 5. Review before merging

Before merging important changes:

- Review the diff.
- Check tests.
- Check for unintended changes.
- Check security implications.
- Verify the intended behavior.

## 6. Never overwrite blindly

Do not force destructive changes when existing work may be lost.

When uncertain, inspect the repository state first.

## 7. Traceability

Important changes should be understandable later through:

- Commit history.
- Pull requests when used.
- Documentation.
- Decision records.
