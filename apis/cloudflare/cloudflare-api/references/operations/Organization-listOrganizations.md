# GET /organizations

**Resource:** [Organizations](../resources/Organizations.md)
**List organizations the user has access to**
**Operation ID:** `Organization_listOrganizations`

Retrieve a list of organizations a particular user has access to. (Currently in Closed Beta - see https://developers.cloudflare.com/fundamentals/organizations/)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**
