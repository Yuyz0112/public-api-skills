# DELETE /organizations/{organization_id}/members/{member_id}

**Resource:** [OrganizationMembers](../resources/OrganizationMembers.md)
**Delete organization member**
**Operation ID:** `Members_delete`

Delete a membership to a particular Organization. (Currently in Closed Beta - see https://developers.cloudflare.com/fundamentals/organizations/)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_id` | path | organizations-api_OrganizationID | Yes |  |
| `member_id` | path | organizations-api_MemberID | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | There is no content to send for this request, but the headers may be useful. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**
