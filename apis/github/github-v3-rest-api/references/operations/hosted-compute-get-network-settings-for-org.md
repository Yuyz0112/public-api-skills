# GET /orgs/{org}/settings/network-settings/{network_settings_id}

**Resource:** [hosted-compute](../resources/hosted-compute.md)
**Get a hosted compute network settings resource for an organization**
**Operation ID:** `hosted-compute/get-network-settings-for-org`

Gets a hosted compute network settings resource configured for an organization.

OAuth app tokens and personal access tokens (classic) need the `read:network_configurations` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[network-settings](../schemas/network-settings/network-settings.md)

