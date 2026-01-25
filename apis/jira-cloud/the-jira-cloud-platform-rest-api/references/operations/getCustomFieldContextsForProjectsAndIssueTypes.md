# POST /rest/api/3/field/{fieldId}/context/mapping

**Resource:** [Issue custom field contexts](../resources/Issue-custom-field-contexts.md)
**Get custom field contexts for projects and issue types**
**Operation ID:** `getCustomFieldContextsForProjectsAndIssueTypes`

Returns a [paginated](#pagination) list of project and issue type mappings and, for each mapping, the ID of a [custom field context](https://confluence.atlassian.com/x/k44fOw) that applies to the project and issue type.

If there is no custom field context assigned to the project then, if present, the custom field context that applies to all projects is returned if it also applies to the issue type or all issue types. If a custom field context is not found, the returned custom field context ID is `null`.

Duplicate project and issue type mappings cannot be provided in the request.

The order of the returned values is the same as provided in the request.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the custom field. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Request Body

The list of project and issue type mappings.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ProjectIssueTypeMappings](../schemas/Project/ProjectIssueTypeMappings.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the custom field, project, or issue type is not found. |

**Success Response Schema:**

[PageBeanContextForProjectAndIssueType](../schemas/Page/PageBeanContextForProjectAndIssueType.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
