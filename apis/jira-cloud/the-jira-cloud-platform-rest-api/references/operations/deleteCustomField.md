# DELETE /rest/api/3/field/{id}

**Resource:** [Issue fields](../resources/Issue-fields.md)
**Delete custom field**
**Operation ID:** `deleteCustomField`

Deletes a custom field. The custom field is deleted whether it is in the trash or not. See [Edit or delete a custom field](https://confluence.atlassian.com/x/Z44fOw) for more information on trashing and deleting custom fields.

This operation is [asynchronous](#async). Follow the `location` link in the response to determine the status of the task and use [Get task](#api-rest-api-3-task-taskId-get) to obtain subsequent updates.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a custom field. |

## Responses

| Status | Description |
|--------|-------------|
| 303 | Returned if the request is successful. |
| 400 | Returned if any of these are true:

 *  The custom field is locked.
 *  The custom field is used in a issue security scheme or a permission scheme.
 *  The custom field ID format is incorrect. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the custom field is not found. |
| 409 | Returned if a task to delete the custom field is running. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
