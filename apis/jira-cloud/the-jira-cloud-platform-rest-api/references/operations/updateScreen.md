# PUT /rest/api/3/screens/{screenId}

**Resource:** [Screens](../resources/Screens.md)
**Update screen**
**Operation ID:** `updateScreen`

Updates a screen. Only screens used in classic projects can be updated.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `screenId` | path | integer (int64) | Yes | The ID of the screen. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateScreenDetails](../schemas/Update/UpdateScreenDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the screen is not found. |

**Success Response Schema:**

[Screen](../schemas/Screen/Screen.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
