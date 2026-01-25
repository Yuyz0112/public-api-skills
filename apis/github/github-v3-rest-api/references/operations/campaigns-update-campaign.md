# PATCH /orgs/{org}/campaigns/{campaign_number}

**Resource:** [campaigns](../resources/campaigns.md)
**Update a campaign**
**Operation ID:** `campaigns/update-campaign`

Updates a campaign in an organization.

The authenticated user must be an owner or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `campaign_number` | path | integer | Yes | The campaign number. |

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
| 503 | (reference) |

**Success Response Schema:**

[campaign-summary](../schemas/campaign-summary/campaign-summary.md)

