# POST /orgs/{org}/settings/network-configurations

**Resource:** [hosted-compute](../resources/hosted-compute.md)
**Create a hosted compute network configuration for an organization**
**Operation ID:** `hosted-compute/create-network-configuration-for-org`

Creates a hosted compute network configuration for an organization.

OAuth app tokens and personal access tokens (classic) need the `write:network_configurations` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |

**Success Response Schema:**

[network-configuration](../schemas/network-configuration/network-configuration.md)

