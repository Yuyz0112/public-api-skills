# GET /rest/api/3/config/fieldschemes/{id}/fields

**Resource:** [Field schemes](../resources/Field-schemes.md)
**Search field scheme fields**
**Operation ID:** `searchFieldAssociationSchemeFields`

Search for fields belonging to a given field association scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The starting index of the returned fields. Base index: 0. |
| `maxResults` | query | integer (int32) | No | The maximum number of fields to return per page, maximum allowed value is 100. |
| `fieldId` | query | string[] | No | The field IDs to filter by, if empty then all fields belonging to a field association scheme will be returned |
| `id` | path | integer (int64) | Yes | The scheme ID to search for child fields |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the matching fields, at the specified page of the results. |
| 400 | Returned if the request parameters are invalid (e.g., negative startAt, maxResults exceeding limit, duplicate fieldIds). |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the feature flag is disabled or the scheme ID is not found. |

**Success Response Schema:**

[PageBean2FieldAssociationSchemeFieldSearchResult](../schemas/Page/PageBean2FieldAssociationSchemeFieldSearchResult.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
