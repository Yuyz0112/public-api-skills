# GET /organizations/{organization_id}/members

**Resource:** [OrganizationMembers](../resources/OrganizationMembers.md)
**List organization members**
**Operation ID:** `Members_list`

List memberships for an Organization. (Currently in Closed Beta - see https://developers.cloudflare.com/fundamentals/organizations/)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_id` | path | organizations-api_OrganizationID | Yes |  |
| `status` | query | string[] | No | Filter the list of memberships by membership status. |
| `user.email` | query | string | No | Filter the list of memberships for a specific email. |
| `user.email.contains` | query | string | No | Filter the list of memberships for a specific email that contains a substring. |
| `user.email.startsWith` | query | string | No | Filter the list of memberships for a specific email that starts with a substring. |
| `user.email.endsWith` | query | string | No | Filter the list of memberships for a specific email that ends with a substring. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**
