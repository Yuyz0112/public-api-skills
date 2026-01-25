# GET /rest/api/3/config/fieldschemes/{id}/projects

**Resource:** [Field schemes](../resources/Field-schemes.md)
**Search field scheme projects**
**Operation ID:** `searchFieldAssociationSchemeProjects`

REST Endpoint for searching for projects belonging to a given field association scheme

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The starting index of the returned projects. Base index: 0. |
| `maxResults` | query | integer (int32) | No | The maximum number of projects to return per page, maximum allowed value is 100. |
| `projectId` | query | integer[] | No | The project Ids to filter by, if empty then all projects belonging to a field association scheme will be returned |
| `id` | path | integer (int64) | Yes | The scheme id to search for associated projects |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a paginated list of projects associated with the field association scheme, matching the specified filter criteria. |
| 400 | 400 response |
| 401 | 401 response |
| 403 | 403 response |
| 404 | 404 response |

**Success Response Schema:**

[PageBean2FieldAssociationSchemeProjectSearchResult](../schemas/Page/PageBean2FieldAssociationSchemeProjectSearchResult.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
