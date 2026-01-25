# GET /rest/api/3/fieldconfiguration/{id}/fields

**Resource:** [Issue field configurations](../resources/Issue-field-configurations.md)
**Get field configuration items**
**Operation ID:** `getFieldConfigurationItems`
⚠️ **Deprecated**

Deprecated, use [Field schemes](#api-group-field-schemes) which supports field association schemes.

Returns a [paginated](#pagination) list of all fields for a configuration.

Only the fields from configurations used in company-managed (classic) projects are returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the field configuration. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the field configuration is not found. |

**Success Response Schema:**

[PageBeanFieldConfigurationItem](../schemas/Page/PageBeanFieldConfigurationItem.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
