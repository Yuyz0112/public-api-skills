# PATCH /organizations/{org}/settings/billing/budgets/{budget_id}

**Resource:** [billing](../resources/billing.md)
**Update a budget for an organization**
**Operation ID:** `billing/update-budget-org`

> [!NOTE]
> This endpoint is in public preview and is subject to change.

Updates an existing budget for an organization. The authenticated user must be an organization admin or billing manager.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Budget updated successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | Budget not found or feature not enabled |
| 422 | (reference) |
| 500 | Internal server error |

