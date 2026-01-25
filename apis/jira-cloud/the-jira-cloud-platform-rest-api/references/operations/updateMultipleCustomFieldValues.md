# POST /rest/api/3/app/field/value

**Resource:** [Issue custom field values (apps)](../resources/Issue-custom-field-values-apps.md)
**Update custom fields**
**Operation ID:** `updateMultipleCustomFieldValues`

Updates the value of one or more custom fields on one or more issues. Combinations of custom field and issue should be unique within the request.

Apps can only perform this operation on [custom fields](https://developer.atlassian.com/platform/forge/manifest-reference/modules/jira-custom-field/) and [custom field types](https://developer.atlassian.com/platform/forge/manifest-reference/modules/jira-custom-field-type/) declared in their own manifests.

**[Permissions](#permissions) required:** Only the app that owns the custom field or custom field type can update its values with this operation.

The new `write:app-data:jira` OAuth scope is 100% optional now, and not using it won't break your app. However, we recommend adding it to your app's scope list because we will eventually make it mandatory.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `generateChangelog` | query | boolean | No | Whether to generate a changelog for this update. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [MultipleCustomFieldValuesUpdateDetails](../schemas/Multiple/MultipleCustomFieldValuesUpdateDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 403 | Returned if the request is not authenticated as the app that provided all the fields. |
| 404 | Returned if any field is not found. |

## Security

- **basicAuth**
- **OAuth2**
