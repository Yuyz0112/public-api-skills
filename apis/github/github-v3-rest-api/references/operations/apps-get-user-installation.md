# GET /users/{username}/installation

**Resource:** [apps](../resources/apps.md)
**Get a user installation for the authenticated app**
**Operation ID:** `apps/get-user-installation`

Enables an authenticated GitHub App to find the user’s installation information.

You must use a [JWT](https://docs.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-a-github-app) to access this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[installation](../schemas/installation/installation.md)

