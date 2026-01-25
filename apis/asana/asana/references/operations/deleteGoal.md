# DELETE /goals/{goal_gid}

**Resource:** [Goals](../resources/Goals.md)
**Delete a goal**
**Operation ID:** `deleteGoal`

A specific, existing goal can be deleted by making a DELETE request on the URL for that goal.

Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified goal. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
