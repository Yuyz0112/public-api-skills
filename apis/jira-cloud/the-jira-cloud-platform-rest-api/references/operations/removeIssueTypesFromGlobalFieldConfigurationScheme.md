# POST /rest/api/3/fieldconfigurationscheme/{id}/mapping/delete

**Resource:** [Issue field configurations](../resources/Issue-field-configurations.md)
**Remove issue types from field configuration scheme**
**Operation ID:** `removeIssueTypesFromGlobalFieldConfigurationScheme`

Removes issue types from the field configuration scheme.

This operation can only modify field configuration schemes used in company-managed (classic) projects.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the field configuration scheme. |

## Request Body

The issue type IDs to remove.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueTypeIdsToRemove](../schemas/Issue/IssueTypeIdsToRemove.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the field configuration scheme or the issue types are not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
