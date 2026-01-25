# PUT /zones/{zone_id}/access/apps/{app_id}

**Resource:** [Zone-Level Access applications](../resources/Zone-Level-Access-applications.md)
**Update an Access application**
**Operation ID:** `zone-level-access-applications-update-a-bookmark-application`

Updates an Access application.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_app_id | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [access_apps](../schemas/access/access-apps.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update an Access application response |
| 4XX | Update an Access application response failure |

## Security

- **api_email**
- **api_key**
