# POST /zones/{zone_id}/access/apps

**Resource:** [Zone-Level Access applications](../resources/Zone-Level-Access-applications.md)
**Add an Access application**
**Operation ID:** `zone-level-access-applications-add-a-bookmark-application`

Adds a new application to Access.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [access_apps](../schemas/access/access-apps.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Add an Access application response |
| 4XX | Add an Access application response failure |

## Security

- **api_email**
- **api_key**
