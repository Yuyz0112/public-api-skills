# GET /repos/{owner}/{repo}/hooks/{hook_id}/deliveries/{delivery_id}

**Resource:** [repos](../resources/repos.md)
**Get a delivery for a repository webhook**
**Operation ID:** `repos/get-webhook-delivery`

Returns a delivery for a webhook configured in a repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[hook-delivery](../schemas/hook-delivery/hook-delivery.md)

