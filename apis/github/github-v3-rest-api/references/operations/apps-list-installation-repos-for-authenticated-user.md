# GET /user/installations/{installation_id}/repositories

**Resource:** [apps](../resources/apps.md)
**List repositories accessible to the user access token**
**Operation ID:** `apps/list-installation-repos-for-authenticated-user`

List repositories that the authenticated user has explicit permission (`:read`, `:write`, or `:admin`) to access for an installation.

The authenticated user has explicit permission to access repositories they own, repositories where they are a collaborator, and repositories that they can access through an organization membership.

The access the user has to each repository is included in the hash under the `permissions` key.

## Responses

| Status | Description |
|--------|-------------|
| 200 | The access the user has to each repository is included in the hash under the `permissions` key. |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

