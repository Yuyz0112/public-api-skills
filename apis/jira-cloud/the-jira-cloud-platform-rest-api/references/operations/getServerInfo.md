# GET /rest/api/3/serverInfo

**Resource:** [Server info](../resources/Server-info.md)
**Get Jira instance info**
**Operation ID:** `getServerInfo`

Returns information about the Jira instance.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect. |

**Success Response Schema:**

[ServerInformation](../schemas/Server/ServerInformation.md)

## Security

- **basicAuth**
- **OAuth2**
