# PUT /rest/api/3/issuetypescreenscheme/{issueTypeScreenSchemeId}

**Resource:** [Issue type screen schemes](../resources/Issue-type-screen-schemes.md)
**Update issue type screen scheme**
**Operation ID:** `updateIssueTypeScreenScheme`

Updates an issue type screen scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueTypeScreenSchemeId` | path | string | Yes | The ID of the issue type screen scheme. |

## Request Body

The issue type screen scheme update details.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueTypeScreenSchemeUpdateDetails](../schemas/Issue/IssueTypeScreenSchemeUpdateDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the issue type screen scheme is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
