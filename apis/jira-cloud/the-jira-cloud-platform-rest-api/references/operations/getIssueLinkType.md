# GET /rest/api/3/issueLinkType/{issueLinkTypeId}

**Resource:** [Issue link types](../resources/Issue-link-types.md)
**Get issue link type**
**Operation ID:** `getIssueLinkType`

Returns an issue link type.

To use this operation, the site must have [issue linking](https://confluence.atlassian.com/x/yoXKM) enabled.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for a project in the site.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueLinkTypeId` | path | string | Yes | The ID of the issue link type. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the issue link type ID is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  issue linking is disabled.
 *  the issue link type is not found.
 *  the user does not have the required permissions. |

**Success Response Schema:**

[IssueLinkType](../schemas/Issue/IssueLinkType.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
