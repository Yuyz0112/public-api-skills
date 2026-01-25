# PUT /rest/api/3/issueLinkType/{issueLinkTypeId}

**Resource:** [Issue link types](../resources/Issue-link-types.md)
**Update issue link type**
**Operation ID:** `updateIssueLinkType`

Updates an issue link type.

To use this operation, the site must have [issue linking](https://confluence.atlassian.com/x/yoXKM) enabled.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueLinkTypeId` | path | string | Yes | The ID of the issue link type. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueLinkType](../schemas/Issue/IssueLinkType.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the issue link type ID or the request body are invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  issue linking is disabled.
 *  the issue link type is not found.
 *  the user does not have the required permissions. |

**Success Response Schema:**

[IssueLinkType](../schemas/Issue/IssueLinkType.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
