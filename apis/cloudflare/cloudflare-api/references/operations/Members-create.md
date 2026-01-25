# POST /organizations/{organization_id}/members

**Resource:** [OrganizationMembers](../resources/OrganizationMembers.md)
**Create organization member**
**Operation ID:** `Members_create`

Create a membership that grants access to a specific Organization. (Currently in Closed Beta - see https://developers.cloudflare.com/fundamentals/organizations/)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_id` | path | organizations-api_OrganizationID | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [organizations-api_CreateMemberRequest](../schemas/organizations-api/organizations-api-CreateMemberRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**
