# GET /user/installations

**Resource:** [apps](../resources/apps.md)
**List app installations accessible to the user access token**
**Operation ID:** `apps/list-installations-for-authenticated-user`

Lists installations of your GitHub App that the authenticated user has explicit permission (`:read`, `:write`, or `:admin`) to access.

The authenticated user has explicit permission to access repositories they own, repositories where they are a collaborator, and repositories that they can access through an organization membership.

You can find the permissions for the installation under the `permissions` key.

## Responses

| Status | Description |
|--------|-------------|
| 200 | You can find the permissions for the installation under the `permissions` key. |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

