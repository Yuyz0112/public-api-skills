# PUT /zones/{zone_id}/access/apps/{app_id}/policies/{policy_id}

**Resource:** [Zone-Level Access policies](../resources/Zone-Level-Access-policies.md)
**Update an Access policy**
**Operation ID:** `zone-level-access-policies-update-an-access-policy`

Update a configured Access policy.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `policy_id` | path | access_uuid | Yes |  |
| `app_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update an Access policy response |
| 4XX | Update an Access policy response failure |

**Success Response Schema:**

[access_policies_components-schemas-single_response](../schemas/access/access-policies-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
