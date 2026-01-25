# PATCH /repos/{owner}/{repo}/hooks/{hook_id}

**Resource:** [repos](../resources/repos.md)
**Update a repository webhook**
**Operation ID:** `repos/update-webhook`

Updates a webhook configured in a repository. If you previously had a `secret` set, you must provide the same `secret` or set a new `secret` or the secret will be removed. If you are only updating individual webhook `config` properties, use "[Update a webhook configuration for a repository](/rest/webhooks/repo-config#update-a-webhook-configuration-for-a-repository)."

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[hook](../schemas/hook/hook.md)

