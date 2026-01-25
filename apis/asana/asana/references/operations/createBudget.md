# POST /budgets

**Resource:** [Budgets](../resources/Budgets.md)
**Create a budget**
**Operation ID:** `createBudget`

Creates a new budget.

## Request Body

The budget to create.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created a new budget. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
