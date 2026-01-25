# GET /orgs/{org}/private-registries

**Resource:** [private-registries](../resources/private-registries.md)
**List private registries for an organization**
**Operation ID:** `private-registries/list-org-private-registries`


Lists all private registry configurations available at the organization-level without revealing their encrypted
values.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | (reference) |
| 404 | (reference) |

