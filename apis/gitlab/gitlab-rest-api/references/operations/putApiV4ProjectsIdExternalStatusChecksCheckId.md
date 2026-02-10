# PUT /api/v4/projects/{id}/external_status_checks/{check_id}

**Resource:** [External status checks](../resources/External-status-checks.md)
**Update external status check**
**Operation ID:** `putApiV4ProjectsIdExternalStatusChecksCheckId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `check_id` | path | integer | Yes | ID of an external status check |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesExternalStatusCheck](../schemas/APIEntitiesExternalStatusCheck/APIEntitiesExternalStatusCheck.md)

