# DELETE /rest/api/3/issueLinkType/{issueLinkTypeId}

**Resource:** [Issue link types](../resources/Issue-link-types.md)
**Delete issue link type**
**Operation ID:** `deleteIssueLinkType`

Deletes an issue link type.

To use this operation, the site must have [issue linking](https://confluence.atlassian.com/x/yoXKM) enabled.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueLinkTypeId` | path | string | Yes | The ID of the issue link type. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the issue link type ID is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  issue linking is disabled.
 *  the issue link type is not found.
 *  the user does not have the required permissions. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
