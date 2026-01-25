# POST /rest/api/3/issueLinkType

**Resource:** [Issue link types](../resources/Issue-link-types.md)
**Create issue link type**
**Operation ID:** `createIssueLinkType`

Creates an issue link type. Use this operation to create descriptions of the reasons why issues are linked. The issue link type consists of a name and descriptions for a link's inward and outward relationships.

To use this operation, the site must have [issue linking](https://confluence.atlassian.com/x/yoXKM) enabled.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueLinkType](../schemas/Issue/IssueLinkType.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  issue linking is disabled.
 *  the issue link type name is in use.
 *  the user does not have the required permissions. |

**Success Response Schema:**

[IssueLinkType](../schemas/Issue/IssueLinkType.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
