# GET /repos/{owner}/{repo}/hooks/{hook_id}/deliveries

**Resource:** [repos](../resources/repos.md)
**List deliveries for a repository webhook**
**Operation ID:** `repos/list-webhook-deliveries`

Returns a list of webhook deliveries for a webhook configured in a repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [hook-delivery-item](../schemas/hook-delivery-item/hook-delivery-item.md)

