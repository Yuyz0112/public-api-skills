# PATCH /repos/{owner}/{repo}/hooks/{hook_id}/config

**Resource:** [repos](../resources/repos.md)
**Update a webhook configuration for a repository**
**Operation ID:** `repos/update-webhook-config-for-repo`

Updates the webhook configuration for a repository. To update more information about the webhook, including the `active` state and `events`, use "[Update a repository webhook](/rest/webhooks/repos#update-a-repository-webhook)."

OAuth app tokens and personal access tokens (classic) need the `write:repo_hook` or `repo` scope to use this endpoint.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[webhook-config](../schemas/webhook-config/webhook-config.md)

