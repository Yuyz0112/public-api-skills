# GET /rest/api/3/config/fieldschemes

**Resource:** [Field schemes](../resources/Field-schemes.md)
**Get field schemes**
**Operation ID:** `getFieldAssociationSchemes`

REST endpoint for retrieving a paginated list of field association schemes with optional filtering.

This endpoint allows clients to fetch field association schemes with optional filtering by project IDs and text queries. The response includes scheme details with navigation links and filter metadata when applicable.

Filtering Behavior:

 *  When projectId or query parameters are provided, the response includes matchedFilters metadata showing which filters were applied.
 *  When no filters are applied, matchedFilters is omitted from individual scheme objects

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectId` | query | integer[] | No | (optional) List of project IDs to filter schemes by. If not provided, schemes from all projects are returned. |
| `query` | query | string | No | (optional) Text filter for scheme name or description matching (case-insensitive). If not provided, no text filtering is applied. |
| `startAt` | query | integer (int64) | No | Zero-based index of the first item to return (default: 0) |
| `maxResults` | query | integer (int32) | No | Maximum number of items to return per page (default: 50, max: 100) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Pagianted list of field association schemes |
| 400 | Returned if the request parameters are invalid (e.g., negative startAt, maxResults exceeding limit). |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the feature flag is disabled. |

**Success Response Schema:**

[PageBean2GetFieldAssociationSchemeResponse](../schemas/Page/PageBean2GetFieldAssociationSchemeResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
