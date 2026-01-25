# DELETE /rest/api/3/config/fieldschemes/{id}

**Resource:** [Field schemes](../resources/Field-schemes.md)
**Delete a field scheme**
**Operation ID:** `deleteFieldAssociationScheme`

Delete a specified field association scheme

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the field association scheme to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the field association scheme deletion was successful. |
| 400 | Returned if the scheme that the user is attempting to delete is a system scheme. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions |
| 404 | Return if the provided ID does not match any existing field association scheme |
| 409 | Return if the scheme that the user is attempting to delete is still in use. |

**Success Response Schema:**

[DeleteFieldAssociationSchemeResponse](../schemas/Delete/DeleteFieldAssociationSchemeResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
