# GET /orgs/{org}/dependabot/secrets

**Resource:** [dependabot](../resources/dependabot.md)
**List organization secrets**
**Operation ID:** `dependabot/list-org-secrets`

Lists all secrets available in an organization without revealing their
encrypted values.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

