# GET /orgs/{org}/private-registries/{secret_name}

**Resource:** [private-registries](../resources/private-registries.md)
**Get a private registry for an organization**
**Operation ID:** `private-registries/get-org-private-registry`


Get the configuration of a single private registry defined for an organization, omitting its encrypted value.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | The specified private registry configuration for the organization |
| 404 | (reference) |

**Success Response Schema:**

[org-private-registry-configuration](../schemas/org-private-registry-configuration/org-private-registry-configuration.md)

