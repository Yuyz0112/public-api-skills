# POST /organizations

**Resource:** [Organizations](../resources/Organizations.md)
**Create organization**
**Operation ID:** `Organizations_createUserOrganization`

Create a new organization for a user. (Currently in Closed Beta - see https://developers.cloudflare.com/fundamentals/organizations/)

## Request Body

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
