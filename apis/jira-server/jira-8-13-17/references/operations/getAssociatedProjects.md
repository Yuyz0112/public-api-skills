# GET /issuetypescheme/{schemeId}/associations

**Resource:** [issuetypescheme](../resources/issuetypescheme.md)
**Operation ID:** `getAssociatedProjects`

For the specified issue type scheme, returns all of the associated projects. (Admin required)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string | No | the parameters to expand on the returned projects; defaults to none. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

