# DELETE /organizations/{organization_id}

**Resource:** [Organizations](../resources/Organizations.md)
**Delete organization.**
**Operation ID:** `Organizations_delete`

Delete an organization. The organization MUST be empty before deleting.
It must not contain any sub-organizations, accounts, members or users. (Currently in Closed Beta - see https://developers.cloudflare.com/fundamentals/organizations/)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_id` | path | organizations-api_OrganizationID | Yes | The ID of the organization to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**
