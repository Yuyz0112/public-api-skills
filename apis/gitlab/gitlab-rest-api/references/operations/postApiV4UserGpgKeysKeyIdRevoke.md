# POST /api/v4/user/gpg_keys/{key_id}/revoke

**Resource:** [Keys](../resources/Keys.md)
**Revoke a GPG key owned by currently authenticated user**
**Operation ID:** `postApiV4UserGpgKeysKeyIdRevoke`

This feature was added in GitLab 10.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key_id` | path | integer | Yes | The ID of the GPG key |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

