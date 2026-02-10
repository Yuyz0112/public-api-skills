# DELETE /api/v4/user/gpg_keys/{key_id}

**Resource:** [Keys](../resources/Keys.md)
**Delete a GPG key from the currently authenticated user**
**Operation ID:** `deleteApiV4UserGpgKeysKeyId`

This feature was added in GitLab 10.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key_id` | path | integer | Yes | The ID of the SSH key |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

