# Debugging

Debugging should be a structured investigation rather than guessing.

## 1. Reproduce the problem

Before changing code, determine:

- What is failing?
- How can the failure be reproduced?
- Under what conditions does it happen?
- Is it consistent or intermittent?

## 2. Observe evidence

Collect relevant evidence such as:

- Error messages.
- Logs.
- Stack traces.
- Inputs.
- Outputs.
- System state.
- Recent changes.

Do not assume the cause before examining evidence.

## 3. Form hypotheses

Identify possible causes and rank them by likelihood and impact.

Test hypotheses systematically.

## 4. Isolate the cause

Reduce the problem to the smallest relevant component or condition possible.

Avoid changing many unrelated things at once.

## 5. Fix the root cause

Prefer fixing the underlying cause rather than hiding the symptom.

If a workaround is necessary, document why.

## 6. Validate the fix

After fixing:

- Reproduce the original scenario.
- Verify the expected behavior.
- Run relevant tests.
- Check for regressions.

## 7. Learn from bugs

For significant bugs, record:

- Cause.
- Impact.
- Fix.
- Why existing controls did not prevent it.
- How to reduce the chance of recurrence.
