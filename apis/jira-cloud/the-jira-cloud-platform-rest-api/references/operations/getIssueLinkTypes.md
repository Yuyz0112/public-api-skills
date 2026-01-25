# GET /rest/api/3/issueLinkType

**Resource:** [Issue link types](../resources/Issue-link-types.md)
**Get issue link types**
**Operation ID:** `getIssueLinkTypes`

Returns a list of all issue link types.

To use this operation, the site must have [issue linking](https://confluence.atlassian.com/x/yoXKM) enabled.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for a project in the site.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if issue linking is disabled. |

**Success Response Schema:**

[IssueLinkTypes](../schemas/Issue/IssueLinkTypes.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
