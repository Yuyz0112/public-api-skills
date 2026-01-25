# GET /repos/{owner}/{repo}/hooks/{hook_id}/config

**Resource:** [repos](../resources/repos.md)
**Get a webhook configuration for a repository**
**Operation ID:** `repos/get-webhook-config-for-repo`

Returns the webhook configuration for a repository. To get more information about the webhook, including the `active` state and `events`, use "[Get a repository webhook](/rest/webhooks/repos#get-a-repository-webhook)."

OAuth app tokens and personal access tokens (classic) need the `read:repo_hook` or `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[webhook-config](../schemas/webhook-config/webhook-config.md)

