# POST /zones/{zone_id}/access/apps/{app_id}/policies

**Resource:** [Zone-Level Access policies](../resources/Zone-Level-Access-policies.md)
**Create an Access policy**
**Operation ID:** `zone-level-access-policies-create-an-access-policy`

Create a new Access policy for an application.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_uuid | Yes |  |
| `zone_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Create an Access policy response |
| 4XX | Create an Access policy response failure |

**Success Response Schema:**

[access_policies_components-schemas-single_response](../schemas/access/access-policies-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
