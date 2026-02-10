# POST /api/v4/namespaces/{id}/minutes

**Resource:** [CI minutes](../resources/CI-minutes.md)
**[DEPRECATED] Create a compute minutes purchase record for the namespace**
**Operation ID:** `postApiV4NamespacesIdMinutes`

Creates an additional pack

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a namespace |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiMinutesAdditionalPack](../schemas/APIEntitiesCiMinutesAdditionalPack/APIEntitiesCiMinutesAdditionalPack.md)

