# GET /api/v4/geo/repositories/{gl_repository}/pipeline_refs

**Resource:** [Geo](../resources/Geo.md)
**Returns the list of pipeline refs for the project**
**Operation ID:** `getApiV4GeoRepositoriesGlRepositoryPipelineRefs`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `gl_repository` | path | string | Yes | The repository to check |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 404 | 404 Not found |

**Success Response Schema:**

[APIEntitiesGeoPipelineRefs](../schemas/APIEntitiesGeoPipelineRefs/APIEntitiesGeoPipelineRefs.md)

