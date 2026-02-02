# DELETE /component/{id}

**Resource:** [component](../resources/component.md)
**Operation ID:** `delete`

Delete a project component.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `moveIssuesTo` | query | string | No | The new component applied to issues whose 'id' component will be deleted.
                     If this value is null, then the 'id' component is simply removed from the related isues. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

