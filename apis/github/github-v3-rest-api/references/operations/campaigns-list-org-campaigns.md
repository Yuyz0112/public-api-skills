# GET /orgs/{org}/campaigns

**Resource:** [campaigns](../resources/campaigns.md)
**List campaigns for an organization**
**Operation ID:** `campaigns/list-org-campaigns`

Lists campaigns in an organization.

The authenticated user must be an owner or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `state` | query | campaign-state | No | If specified, only campaigns with this state will be returned. |
| `sort` | query | enum: created, updated, ends_at... | No | The property by which to sort the results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

Array of [campaign-summary](../schemas/campaign-summary/campaign-summary.md)

