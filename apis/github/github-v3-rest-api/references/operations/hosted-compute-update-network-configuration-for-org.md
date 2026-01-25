# PATCH /orgs/{org}/settings/network-configurations/{network_configuration_id}

**Resource:** [hosted-compute](../resources/hosted-compute.md)
**Update a hosted compute network configuration for an organization**
**Operation ID:** `hosted-compute/update-network-configuration-for-org`

Updates a hosted compute network configuration for an organization.

OAuth app tokens and personal access tokens (classic) need the `write:network_configurations` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[network-configuration](../schemas/network-configuration/network-configuration.md)

