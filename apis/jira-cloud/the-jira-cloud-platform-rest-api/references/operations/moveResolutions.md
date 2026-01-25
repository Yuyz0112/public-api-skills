# PUT /rest/api/3/resolution/move

**Resource:** [Issue resolutions](../resources/Issue-resolutions.md)
**Move resolutions**
**Operation ID:** `moveResolutions`

Changes the order of issue resolutions.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ReorderIssueResolutionsRequest](../schemas/Reorder/ReorderIssueResolutionsRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |
| 404 | Returned if the issue resolution isn't found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
