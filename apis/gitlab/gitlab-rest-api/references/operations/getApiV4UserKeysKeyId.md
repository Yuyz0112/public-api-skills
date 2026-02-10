# GET /api/v4/user/keys/{key_id}

**Resource:** [Keys](../resources/Keys.md)
**Get a single key owned by currently authenticated user**
**Operation ID:** `getApiV4UserKeysKeyId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key_id` | path | integer | Yes | The ID of the SSH key |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesSSHKey](../schemas/APIEntitiesSSHKey/APIEntitiesSSHKey.md)

