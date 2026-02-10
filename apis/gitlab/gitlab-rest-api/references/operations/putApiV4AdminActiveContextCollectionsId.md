# PUT /api/v4/admin/active_context/collections/{id}

**Resource:** [Active context](../resources/Active-context.md)
**Update collection options**
**Operation ID:** `putApiV4AdminActiveContextCollectionsId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | Collection name or ID |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Not found |

**Success Response Schema:**

[APIEntitiesAiActiveContextCollection](../schemas/APIEntitiesAiActiveContextCollection/APIEntitiesAiActiveContextCollection.md)

