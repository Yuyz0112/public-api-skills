# PUT /rest/api/3/app/field/{fieldIdOrKey}/value

**Resource:** [Issue custom field values (apps)](../resources/Issue-custom-field-values-apps.md)
**Update custom field value**
**Operation ID:** `updateCustomFieldValue`

Updates the value of a custom field on one or more issues.

Apps can only perform this operation on [custom fields](https://developer.atlassian.com/platform/forge/manifest-reference/modules/jira-custom-field/) and [custom field types](https://developer.atlassian.com/platform/forge/manifest-reference/modules/jira-custom-field-type/) declared in their own manifests.

**[Permissions](#permissions) required:** Only the app that owns the custom field or custom field type can update its values with this operation.

The new `write:app-data:jira` OAuth scope is 100% optional now, and not using it won't break your app. However, we recommend adding it to your app's scope list because we will eventually make it mandatory.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldIdOrKey` | path | string | Yes | The ID or key of the custom field. For example, `customfield_10010`. |
| `generateChangelog` | query | boolean | No | Whether to generate a changelog for this update. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CustomFieldValueUpdateDetails](../schemas/Custom/CustomFieldValueUpdateDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 403 | Returned if the request is not authenticated as the app that provided the field. |
| 404 | Returned if the field is not found. |

## Security

- **basicAuth**
- **OAuth2**
