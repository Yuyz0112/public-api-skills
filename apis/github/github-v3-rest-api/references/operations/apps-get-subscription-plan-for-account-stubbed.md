# GET /marketplace_listing/stubbed/accounts/{account_id}

**Resource:** [apps](../resources/apps.md)
**Get a subscription plan for an account (stubbed)**
**Operation ID:** `apps/get-subscription-plan-for-account-stubbed`

Shows whether the user or organization account actively subscribes to a plan listed by the authenticated GitHub App. When someone submits a plan change that won't be processed until the end of their billing cycle, you will also see the upcoming pending change.

GitHub Apps must use a [JWT](https://docs.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-a-github-app) to access this endpoint. OAuth apps must use [basic authentication](https://docs.github.com/rest/authentication/authenticating-to-the-rest-api#using-basic-authentication) with their client ID and client secret to access this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 401 | (reference) |
| 404 | Not Found when the account has not purchased the listing |

**Success Response Schema:**

[marketplace-purchase](../schemas/marketplace-purchase/marketplace-purchase.md)

