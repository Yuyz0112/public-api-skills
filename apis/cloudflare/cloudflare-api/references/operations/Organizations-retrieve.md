# GET /organizations/{organization_id}

**Resource:** [Organizations](../resources/Organizations.md)
**Get organization**
**Operation ID:** `Organizations_retrieve`

Retrieve the details of a certain organization. (Currently in Closed Beta - see https://developers.cloudflare.com/fundamentals/organizations/)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_id` | path | organizations-api_OrganizationID | Yes | The ID of the organization to retrieve. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**
