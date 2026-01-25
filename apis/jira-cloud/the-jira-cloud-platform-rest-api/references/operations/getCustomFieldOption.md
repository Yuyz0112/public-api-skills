# GET /rest/api/3/customFieldOption/{id}

**Resource:** [Issue custom field options](../resources/Issue-custom-field-options.md)
**Get custom field option**
**Operation ID:** `getCustomFieldOption`

Returns a custom field option. For example, an option in a select list.

Note that this operation **only works for issue field select list options created in Jira or using operations from the [Issue custom field options](#api-group-Issue-custom-field-options) resource**, it cannot be used with issue field select list options created by Connect apps.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** The custom field option is returned as follows:

 *  if the user has the *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).
 *  if the user has the *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for at least one project the custom field is used in, and the field is visible in at least one layout the user has permission to view.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the custom field option. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  the custom field option is not found.
 *  the user does not have permission to view the custom field. |

**Success Response Schema:**

[CustomFieldOption](../schemas/Custom/CustomFieldOption.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
