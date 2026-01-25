# POST /v1/apps/secrets

**Resource:** [apps](../resources/apps.md)
**Set a Secret**
**Operation ID:** `PostAppsSecrets`

<p>Create or replace a secret in the secret store.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[apps.secret](../schemas/apps-secret/apps-secret.md)

