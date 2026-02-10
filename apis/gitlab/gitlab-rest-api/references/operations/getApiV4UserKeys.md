# GET /api/v4/user/keys

**Resource:** [Keys](../resources/Keys.md)
**Get the currently authenticated user's SSH keys**
**Operation ID:** `getApiV4UserKeys`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesSSHKey](../schemas/APIEntitiesSSHKey/APIEntitiesSSHKey.md)

