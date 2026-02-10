# POST /api/v4/applications/{id}/renew-secret

**Resource:** [Applications](../resources/Applications.md)
**Renew an application secret**
**Operation ID:** `postApiV4ApplicationsIdRenewSecret`

Renew the secret of a specific application

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the application (not the application_id) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesApplicationWithSecret](../schemas/APIEntitiesApplicationWithSecret/APIEntitiesApplicationWithSecret.md)

