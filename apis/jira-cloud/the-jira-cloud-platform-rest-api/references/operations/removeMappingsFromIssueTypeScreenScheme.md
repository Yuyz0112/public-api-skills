# POST /rest/api/3/issuetypescreenscheme/{issueTypeScreenSchemeId}/mapping/remove

**Resource:** [Issue type screen schemes](../resources/Issue-type-screen-schemes.md)
**Remove mappings from issue type screen scheme**
**Operation ID:** `removeMappingsFromIssueTypeScreenScheme`

Removes issue type to screen scheme mappings from an issue type screen scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueTypeScreenSchemeId` | path | string | Yes | The ID of the issue type screen scheme. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueTypeIds](../schemas/Issue/IssueTypeIds.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the screen scheme mappings are removed from the issue type screen scheme. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the issue type screen scheme or one or more issue type mappings are not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
