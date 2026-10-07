# Security

Security is a responsibility throughout development and operation.

## 1. Protect secrets

Never commit or expose:

- Passwords.
- API keys.
- Access tokens.
- Private keys.
- Credentials.
- Sensitive configuration.

Use appropriate secret management mechanisms.

## 2. Validate input

Treat external input as untrusted.

Validate data before using it in:

- Database operations.
- Commands.
- Queries.
- File operations.
- APIs.
- Authentication flows.

## 3. Authentication and authorization

Authentication determines who someone is.

Authorization determines what they are allowed to do.

Both must be implemented deliberately.

## 4. Least privilege

Users, applications, services, and integrations should receive only the permissions they need.

## 5. Sensitive data

Identify sensitive information and minimize:

- Collection.
- Storage.
- Exposure.
- Logging.
- Retention.

## 6. Dependencies

Monitor dependencies for known security problems and avoid unnecessary dependencies.

## 7. Failure behavior

Systems should fail safely.

Errors should not reveal secrets, internal architecture, credentials, or unnecessary sensitive information.

## 8. External integrations

Treat external APIs and services as security boundaries.

Protect credentials and validate responses.

## 9. Security review

For important changes, ask:

- What could an attacker control?
- What sensitive data could be exposed?
- What permissions are involved?
- What happens if validation fails?
- What happens if an external service is compromised?

## 10. Incident response

If a security problem is discovered:

1. Contain the problem.
2. Determine the scope.
3. Protect affected credentials or data.
4. Fix the vulnerability.
5. Validate the fix.
6. Document the incident.
7. Improve the system to reduce recurrence.
