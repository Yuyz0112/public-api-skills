# GET /v1/apps/secrets/find

**Resource:** [apps](../resources/apps.md)
**Find a Secret**
**Operation ID:** `GetAppsSecretsFind`

<p>Finds a secret in the secret store by name and scope.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `name` | query | string | Yes | A name for the secret that's unique within the scope. |
| `scope` | query | object | Yes | Specifies the scoping of the secret. Requests originating from UI extensions can only access account-scoped secrets or secrets scoped to their own user. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[apps.secret](../schemas/apps-secret/apps-secret.md)

