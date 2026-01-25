# PATCH /repos/{owner}/{repo}/import/authors/{author_id}

**Resource:** [migrations](../resources/migrations.md)
**Map a commit author**
**Operation ID:** `migrations/map-commit-author`
⚠️ **Deprecated**

Update an author's identity for the import. Your application can continue updating authors any time before you push
new commits to the repository.

> [!WARNING]
> **Endpoint closing down notice:** Due to very low levels of usage and available alternatives, this endpoint is closing down and will no longer be available from 00:00 UTC on April 12, 2024. For more details and alternatives, see the [changelog](https://gh.io/source-imports-api-deprecation).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `author_id` | path | integer | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 422 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[porter-author](../schemas/porter-author/porter-author.md)

