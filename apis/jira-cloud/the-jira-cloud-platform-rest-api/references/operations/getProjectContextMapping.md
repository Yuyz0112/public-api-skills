# GET /rest/api/3/field/{fieldId}/context/projectmapping

**Resource:** [Issue custom field contexts](../resources/Issue-custom-field-contexts.md)
**Get project mappings for custom field context**
**Operation ID:** `getProjectContextMapping`

Returns a [paginated](#pagination) list of context to project mappings for a custom field. The result can be filtered by `contextId`. Otherwise, all mappings are returned. Invalid IDs are ignored.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the custom field, for example `customfield\_10000`. |
| `contextId` | query | integer[] | No | The list of context IDs. To include multiple context, separate IDs with ampersand: `contextId=10000&contextId=10001`. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the custom field is not found. |

**Success Response Schema:**

[PageBeanCustomFieldContextProjectMapping](../schemas/Page/PageBeanCustomFieldContextProjectMapping.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
