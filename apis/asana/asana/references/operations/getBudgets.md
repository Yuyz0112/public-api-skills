# GET /budgets

**Resource:** [Budgets](../resources/Budgets.md)
**Get all budgets**
**Operation ID:** `getBudgets`

Gets all budgets for a given *parent*. This will at most return a list of size 1 for a given *parent*.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `parent` | query | string | Yes | Globally unique identifier for the budget's parent object. This currently can only be a `project`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested budgets. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
