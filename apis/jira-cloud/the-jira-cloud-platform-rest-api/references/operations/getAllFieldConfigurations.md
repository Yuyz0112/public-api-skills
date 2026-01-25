# GET /rest/api/3/fieldconfiguration

**Resource:** [Issue field configurations](../resources/Issue-field-configurations.md)
**Get all field configurations**
**Operation ID:** `getAllFieldConfigurations`
⚠️ **Deprecated**

Deprecated, use [Field schemes](#api-group-field-schemes) which supports field association schemes.

Returns a [paginated](#pagination) list of field configurations. The list can be for all field configurations or a subset determined by any combination of these criteria:

 *  a list of field configuration item IDs.
 *  whether the field configuration is a default.
 *  whether the field configuration name or description contains a query string.

Only field configurations used in company-managed (classic) projects are returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `id` | query | integer[] | No | The list of field configuration IDs. To include multiple IDs, provide an ampersand-separated list. For example, `id=10000&id=10001`. |
| `isDefault` | query | boolean | No | If *true* returns default field configurations only. |
| `query` | query | string | No | The query string used to match against field configuration names and descriptions. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[PageBeanFieldConfigurationDetails](../schemas/Page/PageBeanFieldConfigurationDetails.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
