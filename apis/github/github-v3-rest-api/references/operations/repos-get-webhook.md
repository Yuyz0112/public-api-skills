# GET /repos/{owner}/{repo}/hooks/{hook_id}

**Resource:** [repos](../resources/repos.md)
**Get a repository webhook**
**Operation ID:** `repos/get-webhook`

Returns a webhook configured in a repository. To get only the webhook `config` properties, see "[Get a webhook configuration for a repository](/rest/webhooks/repo-config#get-a-webhook-configuration-for-a-repository)."

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[hook](../schemas/hook/hook.md)

