# GET /rest/api/3/app/field/{fieldIdOrKey}/context/configuration

**Resource:** [Issue custom field configuration (apps)](../resources/Issue-custom-field-configuration-apps.md)
**Get custom field configurations**
**Operation ID:** `getCustomFieldConfiguration`

Returns a [paginated](#pagination) list of configurations for a custom field of a [type](https://developer.atlassian.com/platform/forge/manifest-reference/modules/jira-custom-field-type/) created by a [Forge app](https://developer.atlassian.com/platform/forge/).

The result can be filtered by one of these criteria:

 *  `id`.
 *  `fieldContextId`.
 *  `issueId`.
 *  `projectKeyOrId` and `issueTypeId`.

Otherwise, all configurations are returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg). Jira permissions are not required for the Forge app that provided the custom field type.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldIdOrKey` | path | string | Yes | The ID or key of the custom field, for example `customfield_10000`. |
| `id` | query | integer[] | No | The list of configuration IDs. To include multiple configurations, separate IDs with an ampersand: `id=10000&id=10001`. Can't be provided with `fieldContextId`, `issueId`, `projectKeyOrId`, or `issueTypeId`. |
| `fieldContextId` | query | integer[] | No | The list of field context IDs. To include multiple field contexts, separate IDs with an ampersand: `fieldContextId=10000&fieldContextId=10001`. Can't be provided with `id`, `issueId`, `projectKeyOrId`, or `issueTypeId`. |
| `issueId` | query | integer (int64) | No | The ID of the issue to filter results by. If the issue doesn't exist, an empty list is returned. Can't be provided with `projectKeyOrId`, or `issueTypeId`. |
| `projectKeyOrId` | query | string | No | The ID or key of the project to filter results by. Must be provided with `issueTypeId`. Can't be provided with `issueId`. |
| `issueTypeId` | query | string | No | The ID of the issue type to filter results by. Must be provided with `projectKeyOrId`. Can't be provided with `issueId`. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user is not a Jira admin or the request is not authenticated as from the app that provided the field. |
| 404 | Returned if the custom field is not found. |

**Success Response Schema:**

[PageBeanContextualConfiguration](../schemas/Page/PageBeanContextualConfiguration.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
