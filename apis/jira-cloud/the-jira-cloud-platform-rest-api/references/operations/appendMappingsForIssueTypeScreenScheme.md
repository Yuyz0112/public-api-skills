# PUT /rest/api/3/issuetypescreenscheme/{issueTypeScreenSchemeId}/mapping

**Resource:** [Issue type screen schemes](../resources/Issue-type-screen-schemes.md)
**Append mappings to issue type screen scheme**
**Operation ID:** `appendMappingsForIssueTypeScreenScheme`

Appends issue type to screen scheme mappings to an issue type screen scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueTypeScreenSchemeId` | path | string | Yes | The ID of the issue type screen scheme. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueTypeScreenSchemeMappingDetails](../schemas/Issue/IssueTypeScreenSchemeMappingDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the issue type screen scheme, issue type, or screen scheme is not found. |
| 409 | Returned if the issue type is a sub-task, but sub-tasks are disabled in Jira settings. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
