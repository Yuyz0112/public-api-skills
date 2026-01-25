# POST /repos/{owner}/{repo}/hooks

**Resource:** [repos](../resources/repos.md)
**Create a repository webhook**
**Operation ID:** `repos/create-webhook`

Repositories can have multiple webhooks installed. Each webhook should have a unique `config`. Multiple webhooks can
share the same `config` as long as those webhooks do not have any `events` that overlap.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[hook](../schemas/hook/hook.md)

