# GET /organizations/{organization_id}/members/{member_id}

**Resource:** [OrganizationMembers](../resources/OrganizationMembers.md)
**Get organization member**
**Operation ID:** `Members_retrieve`

Retrieve a single membership from an Organization. (Currently in Closed Beta - see https://developers.cloudflare.com/fundamentals/organizations/)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_id` | path | organizations-api_OrganizationID | Yes |  |
| `member_id` | path | organizations-api_MemberID | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**
