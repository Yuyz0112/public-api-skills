# DELETE /orgs/{org}/campaigns/{campaign_number}

**Resource:** [campaigns](../resources/campaigns.md)
**Delete a campaign for an organization**
**Operation ID:** `campaigns/delete-campaign`

Deletes a campaign in an organization.

The authenticated user must be an owner or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `campaign_number` | path | integer | Yes | The campaign number. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Deletion successful |
| 404 | (reference) |
| 503 | (reference) |

