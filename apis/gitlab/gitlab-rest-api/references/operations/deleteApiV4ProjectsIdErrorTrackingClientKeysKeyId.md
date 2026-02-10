# DELETE /api/v4/projects/{id}/error_tracking/client_keys/{key_id}

**Resource:** [Error tracking](../resources/Error-tracking.md)
**Delete a client key**
**Operation ID:** `deleteApiV4ProjectsIdErrorTrackingClientKeysKeyId`

Removes a client key from the project. This feature was introduced in GitLab 14.3.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

