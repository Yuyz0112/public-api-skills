# GET /api/v4/keys

**Resource:** [Keys](../resources/Keys.md)
**Get user by fingerprint of SSH key**
**Operation ID:** `getApiV4Keys`

You can search for a user that owns a specific SSH key. Note only administrators can lookup SSH key\
        with the fingerprint of an SSH key

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fingerprint` | query | string | Yes | The fingerprint of an SSH key |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesUserWithAdmin](../schemas/APIEntitiesUserWithAdmin/APIEntitiesUserWithAdmin.md)

