# GET /orgs/{org}/migrations

**Resource:** [migrations](../resources/migrations.md)
**List organization migrations**
**Operation ID:** `migrations/list-for-org`

Lists the most recent migrations, including both exports (which can be started through the REST API) and imports (which cannot be started using the REST API).

A list of `repositories` is only returned for export migrations.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `exclude` | query | string[] | No | Exclude attributes from the API response to improve performance |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [migration](../schemas/migration/migration.md)

