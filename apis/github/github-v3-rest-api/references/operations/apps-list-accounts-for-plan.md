# GET /marketplace_listing/plans/{plan_id}/accounts

**Resource:** [apps](../resources/apps.md)
**List accounts for a plan**
**Operation ID:** `apps/list-accounts-for-plan`

Returns user and organization accounts associated with the specified plan, including free plans. For per-seat pricing, you see the list of accounts that have purchased the plan, including the number of seats purchased. When someone submits a plan change that won't be processed until the end of their billing cycle, you will also see the upcoming pending change.

GitHub Apps must use a [JWT](https://docs.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-a-github-app) to access this endpoint. OAuth apps must use [basic authentication](https://docs.github.com/rest/authentication/authenticating-to-the-rest-api#using-basic-authentication) with their client ID and client secret to access this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `direction` | query | enum: asc, desc | No | To return the oldest accounts first, set to `asc`. Ignored without the `sort` parameter. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 401 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [marketplace-purchase](../schemas/marketplace-purchase/marketplace-purchase.md)

