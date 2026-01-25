# POST /v1/apps/secrets/delete

**Resource:** [apps](../resources/apps.md)
**Delete a Secret**
**Operation ID:** `PostAppsSecretsDelete`

<p>Deletes a secret from the secret store by name and scope.</p>

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

