# GET /zones/{zone_id}/access/apps

**Resource:** [Zone-Level Access applications](../resources/Zone-Level-Access-applications.md)
**List Access Applications**
**Operation ID:** `zone-level-access-applications-list-access-applications`

List all Access Applications in a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Access Applications response |
| 4XX | List Access Applications response failure |

**Success Response Schema:**

[access_apps_components-schemas-response_collection-2](../schemas/access/access-apps-components-schemas-response-collection-2.md)

## Security

- **api_email**
- **api_key**
