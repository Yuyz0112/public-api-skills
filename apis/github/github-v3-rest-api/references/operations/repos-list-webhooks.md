# GET /repos/{owner}/{repo}/hooks

**Resource:** [repos](../resources/repos.md)
**List repository webhooks**
**Operation ID:** `repos/list-webhooks`

Lists webhooks for a repository. `last response` may return null if there have not been any deliveries within 30 days.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [hook](../schemas/hook/hook.md)

