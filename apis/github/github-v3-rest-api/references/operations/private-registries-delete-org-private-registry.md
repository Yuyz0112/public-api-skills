# DELETE /orgs/{org}/private-registries/{secret_name}

**Resource:** [private-registries](../resources/private-registries.md)
**Delete a private registry for an organization**
**Operation ID:** `private-registries/delete-org-private-registry`


Delete a private registry configuration at the organization-level.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 400 | (reference) |
| 404 | (reference) |

