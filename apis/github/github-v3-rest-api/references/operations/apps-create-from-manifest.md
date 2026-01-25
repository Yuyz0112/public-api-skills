# POST /app-manifests/{code}/conversions

**Resource:** [apps](../resources/apps.md)
**Create a GitHub App from a manifest**
**Operation ID:** `apps/create-from-manifest`

Use this endpoint to complete the handshake necessary when implementing the [GitHub App Manifest flow](https://docs.github.com/apps/building-github-apps/creating-github-apps-from-a-manifest/). When you create a GitHub App with the manifest flow, you receive a temporary `code` used to retrieve the GitHub App's `id`, `pem` (private key), and `webhook_secret`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `code` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 404 | (reference) |
| 422 | (reference) |

