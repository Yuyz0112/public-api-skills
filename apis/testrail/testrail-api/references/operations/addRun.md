# POST /index.php?/api/v2/add_run/{project_id}

**Resource:** [runs](../resources/runs.md)
**Add run**
**Operation ID:** `addRun`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [AddRunRequest](../schemas/Add/AddRunRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Created run |
| default | (reference) |

**Success Response Schema:**

[Run](../schemas/Run/Run.md)

## Security

- **basicAuth**
