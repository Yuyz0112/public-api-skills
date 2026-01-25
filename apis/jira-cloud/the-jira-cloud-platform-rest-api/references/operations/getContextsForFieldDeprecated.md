# GET /rest/api/3/field/{fieldId}/contexts

**Resource:** [Issue fields](../resources/Issue-fields.md)
**Get contexts for a field**
**Operation ID:** `getContextsForFieldDeprecated`
⚠️ **Deprecated**

Returns a [paginated](#pagination) list of the contexts a field is used in. Deprecated, use [ Get custom field contexts](#api-rest-api-3-field-fieldId-context-get).

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the field to return contexts for. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[PageBeanContext](../schemas/Page/PageBeanContext.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
