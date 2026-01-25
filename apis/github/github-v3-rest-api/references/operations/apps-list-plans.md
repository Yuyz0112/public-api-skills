# GET /marketplace_listing/plans

**Resource:** [apps](../resources/apps.md)
**List plans**
**Operation ID:** `apps/list-plans`

Lists all plans that are part of your GitHub Marketplace listing.

GitHub Apps must use a [JWT](https://docs.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-a-github-app) to access this endpoint. OAuth apps must use [basic authentication](https://docs.github.com/rest/authentication/authenticating-to-the-rest-api#using-basic-authentication) with their client ID and client secret to access this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 401 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [marketplace-listing-plan](../schemas/marketplace-listing-plan/marketplace-listing-plan.md)

