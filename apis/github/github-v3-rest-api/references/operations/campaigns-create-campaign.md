# POST /orgs/{org}/campaigns

**Resource:** [campaigns](../resources/campaigns.md)
**Create a campaign for an organization**
**Operation ID:** `campaigns/create-campaign`

Create a campaign for an organization.

The authenticated user must be an owner or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint.

Fine-grained tokens must have the "Code scanning alerts" repository permissions (read) on all repositories included
in the campaign.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | Bad Request |
| 404 | (reference) |
| 422 | Unprocessable Entity |
| 429 | Too Many Requests |
| 503 | (reference) |

**Success Response Schema:**

[campaign-summary](../schemas/campaign-summary/campaign-summary.md)

