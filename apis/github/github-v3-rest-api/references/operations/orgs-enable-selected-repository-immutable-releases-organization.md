# PUT /orgs/{org}/settings/immutable-releases/repositories/{repository_id}

**Resource:** [orgs](../resources/orgs.md)
**Enable a selected repository for immutable releases in an organization**
**Operation ID:** `orgs/enable-selected-repository-immutable-releases-organization`

Adds a repository to the list of selected repositories that are enforced for immutable releases in an organization. To use this endpoint, the organization immutable releases policy for `enforced_repositories` must be configured to `selected`.

OAuth tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

