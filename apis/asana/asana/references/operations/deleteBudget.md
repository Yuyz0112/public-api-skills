# DELETE /budgets/{budget_gid}

**Resource:** [Budgets](../resources/Budgets.md)
**Delete a budget**
**Operation ID:** `deleteBudget`

A specific, existing budget can be deleted by making a DELETE request on the URL for that budget.

Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified budget. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
