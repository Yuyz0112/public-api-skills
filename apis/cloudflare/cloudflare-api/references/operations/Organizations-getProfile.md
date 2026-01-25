# GET /organizations/{organization_id}/profile

**Resource:** [Organizations](../resources/Organizations.md)
**Get organization profile**
**Operation ID:** `Organizations_getProfile`

Get an organizations profile if it exists. (Currently in Closed Beta - see https://developers.cloudflare.com/fundamentals/organizations/)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_id` | path | organizations-api_OrganizationID | Yes | The ID of the organization to retrieve a profile for. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**
