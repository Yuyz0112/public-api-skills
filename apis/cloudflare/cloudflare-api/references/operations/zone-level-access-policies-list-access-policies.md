# GET /zones/{zone_id}/access/apps/{app_id}/policies

**Resource:** [Zone-Level Access policies](../resources/Zone-Level-Access-policies.md)
**List Access policies**
**Operation ID:** `zone-level-access-policies-list-access-policies`

Lists Access policies configured for an application.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Access policies response |
| 4XX | List Access policies response failure |

**Success Response Schema:**

[access_policies_components-schemas-response_collection](../schemas/access/access-policies-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
