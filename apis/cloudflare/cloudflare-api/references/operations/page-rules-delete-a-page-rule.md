# DELETE /zones/{zone_id}/pagerules/{pagerule_id}

**Resource:** [Page Rules](../resources/Page-Rules.md)
**Delete a Page Rule**
**Operation ID:** `page-rules-delete-a-page-rule`

Deletes an existing Page Rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `pagerule_id` | path | zones_schemas-identifier | Yes |  |
| `zone_id` | path | zones_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a Page Rule response |
| 4XX | Delete a Page Rule response failure |

**Success Response Schema:**

[zones_schemas-api-response-single-id](../schemas/zones/zones-schemas-api-response-single-id.md)

## Security

- **api_token**
- **api_email**
- **api_key**
