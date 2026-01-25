# PUT /rest/api/3/field/{fieldId}/context/{contextId}

**Resource:** [Issue custom field contexts](../resources/Issue-custom-field-contexts.md)
**Update custom field context**
**Operation ID:** `updateCustomFieldContext`

Updates a [ custom field context](https://confluence.atlassian.com/adminjiracloud/what-are-custom-field-contexts-991923859.html).

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the custom field. |
| `contextId` | path | integer (int64) | Yes | The ID of the context. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CustomFieldContextUpdateDetails](../schemas/Custom/CustomFieldContextUpdateDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the context is updated. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the custom field or the context is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
