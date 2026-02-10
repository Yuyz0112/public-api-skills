# GET /api/v4/projects/{id}/transfer_locations

**Resource:** [Projects](../resources/Projects.md)
**Get the namespaces to where the project can be transferred**
**Operation ID:** `getApiV4ProjectsIdTransferLocations`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `search` | query | string | No | Return list of namespaces matching the search criteria |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Unauthenticated |

**Success Response Schema:**

[APIEntitiesPublicGroupDetails](../schemas/APIEntitiesPublicGroupDetails/APIEntitiesPublicGroupDetails.md)

