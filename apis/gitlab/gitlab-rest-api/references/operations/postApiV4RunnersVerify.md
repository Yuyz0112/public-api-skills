# POST /api/v4/runners/verify

**Resource:** [CI runners](../resources/CI-runners.md)
**Validate authentication credentials**
**Operation ID:** `postApiV4RunnersVerify`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Credentials are valid |
| 201 | Created |
| 403 | Forbidden |
| 422 | Runner is orphaned |

