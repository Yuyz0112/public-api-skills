# GET /rest/api/3/field/{fieldId}/context/issuetypemapping

**Resource:** [Issue custom field contexts](../resources/Issue-custom-field-contexts.md)
**Get issue types for custom field context**
**Operation ID:** `getIssueTypeMappingsForContexts`

Returns a [paginated](#pagination) list of context to issue type mappings for a custom field. Mappings are returned for all contexts or a list of contexts. Mappings are ordered first by context ID and then by issue type ID.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the custom field. |
| `contextId` | query | integer[] | No | The ID of the context. To include multiple contexts, provide an ampersand-separated list. For example, `contextId=10001&contextId=10002`. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if operation is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |

**Success Response Schema:**

[PageBeanIssueTypeToContextMapping](../schemas/Page/PageBeanIssueTypeToContextMapping.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
