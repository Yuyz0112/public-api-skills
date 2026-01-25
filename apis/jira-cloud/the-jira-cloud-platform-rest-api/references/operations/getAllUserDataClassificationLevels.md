# GET /rest/api/3/classification-levels

**Resource:** [Classification levels](../resources/Classification-levels.md)
**Get all classification levels**
**Operation ID:** `getAllUserDataClassificationLevels`

Returns all classification levels.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `status` | query | string[] | No | Optional set of statuses to filter by. |
| `orderBy` | query | enum: rank, -rank, +rank | No | Ordering of the results by a given field. If not provided, values will not be sorted. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[DataClassificationLevelsBean](../schemas/Data/DataClassificationLevelsBean.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
