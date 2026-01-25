# GET /rest/api/3/user/email/bulk

**Resource:** [Users](../resources/Users.md)
**Get user email bulk**
**Operation ID:** `getUserEmailBulk`

Returns a user's email address regardless of the user's profile visibility settings. For Connect apps, this API is only available to apps approved by Atlassian, according to these [guidelines](https://community.developer.atlassian.com/t/guidelines-for-requesting-access-to-email-address/27603). For Forge apps, this API only supports access via asApp() requests.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `accountId` | query | string[] | Yes | The account IDs of the users for which emails are required. An `accountId` is an identifier that uniquely identifies the user across all Atlassian products. For example, `5b10ac8d82e05b22cc7d4ef5`. Note, this should be treated as an opaque identifier (that is, do not assume any structure in the value). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the calling app is not approved to use this API. |
| 401 | Returned if the authentication credentials are incorrect, or missing from the request (for example if a user is trying to access this API). |
| 503 | Indicates the API is not currently enabled. |

**Success Response Schema:**

[UnrestrictedUserEmail](../schemas/Unrestricted/UnrestrictedUserEmail.md)

## Security

- **basicAuth**
