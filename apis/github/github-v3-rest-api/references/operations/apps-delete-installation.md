# DELETE /app/installations/{installation_id}

**Resource:** [apps](../resources/apps.md)
**Delete an installation for the authenticated app**
**Operation ID:** `apps/delete-installation`

Uninstalls a GitHub App on a user, organization, or enterprise account. If you prefer to temporarily suspend an app's access to your account's resources, then we recommend the "[Suspend an app installation](https://docs.github.com/rest/apps/apps#suspend-an-app-installation)" endpoint.

You must use a [JWT](https://docs.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-a-github-app) to access this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |

