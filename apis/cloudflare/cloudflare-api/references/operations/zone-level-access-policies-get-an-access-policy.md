# GET /zones/{zone_id}/access/apps/{app_id}/policies/{policy_id}

**Resource:** [Zone-Level Access policies](../resources/Zone-Level-Access-policies.md)
**Get an Access policy**
**Operation ID:** `zone-level-access-policies-get-an-access-policy`

Fetches a single Access policy.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `policy_id` | path | access_uuid | Yes |  |
| `app_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get an Access policy response |
| 4XX | Get an Access policy response failure |

**Success Response Schema:**

[access_policies_components-schemas-single_response](../schemas/access/access-policies-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
