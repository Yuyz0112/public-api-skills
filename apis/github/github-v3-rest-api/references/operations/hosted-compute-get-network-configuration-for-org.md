# GET /orgs/{org}/settings/network-configurations/{network_configuration_id}

**Resource:** [hosted-compute](../resources/hosted-compute.md)
**Get a hosted compute network configuration for an organization**
**Operation ID:** `hosted-compute/get-network-configuration-for-org`

Gets a hosted compute network configuration configured in an organization.

OAuth app tokens and personal access tokens (classic) need the `read:network_configurations` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[network-configuration](../schemas/network-configuration/network-configuration.md)

