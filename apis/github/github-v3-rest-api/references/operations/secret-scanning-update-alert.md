# PATCH /repos/{owner}/{repo}/secret-scanning/alerts/{alert_number}

**Resource:** [secret-scanning](../resources/secret-scanning.md)
**Update a secret scanning alert**
**Operation ID:** `secret-scanning/update-alert`

Updates the status of a secret scanning alert in an eligible repository.

You can also use this endpoint to assign or unassign an alert to a user who has write access to the repository.

The authenticated user must be an administrator for the repository or for the organization that owns the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` or `security_events` scope to use this endpoint. If this endpoint is only used with public repositories, the token can use the `public_repo` scope instead.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | Bad request, resolution comment is invalid or the resolution was not changed. |
| 404 | Repository is public, or secret scanning is disabled for the repository, or the resource is not found |
| 422 | State does not match the resolution or resolution comment, or assignee does not have write access to the repository |
| 503 | (reference) |

**Success Response Schema:**

[secret-scanning-alert](../schemas/secret-scanning-alert/secret-scanning-alert.md)

