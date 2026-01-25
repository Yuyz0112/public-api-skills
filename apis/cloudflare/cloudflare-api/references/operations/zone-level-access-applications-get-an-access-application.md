# GET /zones/{zone_id}/access/apps/{app_id}

**Resource:** [Zone-Level Access applications](../resources/Zone-Level-Access-applications.md)
**Get an Access application**
**Operation ID:** `zone-level-access-applications-get-an-access-application`

Fetches information about an Access application.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_app_id | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get an Access application response |
| 4XX | Get an Access application response failure |

**Success Response Schema:**

[access_apps_components-schemas-single_response-2](../schemas/access/access-apps-components-schemas-single-response-2.md)

## Security

- **api_email**
- **api_key**
