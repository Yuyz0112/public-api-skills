# GET /rest/api/3/fieldconfigurationscheme

**Resource:** [Issue field configurations](../resources/Issue-field-configurations.md)
**Get all field configuration schemes**
**Operation ID:** `getAllFieldConfigurationSchemes`

Returns a [paginated](#pagination) list of field configuration schemes.

Only field configuration schemes used in classic projects are returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `id` | query | integer[] | No | The list of field configuration scheme IDs. To include multiple IDs, provide an ampersand-separated list. For example, `id=10000&id=10001`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permissions. |

**Success Response Schema:**

[PageBeanFieldConfigurationScheme](../schemas/Page/PageBeanFieldConfigurationScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
