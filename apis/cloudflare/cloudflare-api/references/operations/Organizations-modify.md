# PUT /organizations/{organization_id}

**Resource:** [Organizations](../resources/Organizations.md)
**Modify organization.**
**Operation ID:** `Organizations_modify`

Modify organization. (Currently in Closed Beta - see https://developers.cloudflare.com/fundamentals/organizations/)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_id` | path | organizations-api_OrganizationID | Yes | The ID of the organization to modify. |

## Request Body

The new details of the organization. Only accepts updates
to "name" currently.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [organizations-api_Organization](../schemas/organizations-api/organizations-api-Organization.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**
