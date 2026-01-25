# DELETE /zones/{zone_id}/access/apps/{app_id}

**Resource:** [Zone-Level Access applications](../resources/Zone-Level-Access-applications.md)
**Delete an Access application**
**Operation ID:** `zone-level-access-applications-delete-an-access-application`

Deletes an application from Access.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_app_id | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Delete an Access application response |
| 4XX | Delete an Access application response failure |

## Security

- **api_email**
- **api_key**
