# POST /organizations/{organization_id}/members:batchCreate

**Resource:** [OrganizationMembers](../resources/OrganizationMembers.md)
**Batch create organization members**
**Operation ID:** `Members_batchCreate`

Batch create multiple memberships that grant access to a specific Organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_id` | path | organizations-api_OrganizationID | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [organizations-api_BatchCreateMembersRequest](../schemas/organizations-api/organizations-api-BatchCreateMembersRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**
