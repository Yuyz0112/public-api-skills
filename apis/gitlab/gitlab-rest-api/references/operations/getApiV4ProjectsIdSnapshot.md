# GET /api/v4/projects/{id}/snapshot

**Resource:** [Project snapshots](../resources/Project-snapshots.md)
**Download a (possibly inconsistent) snapshot of a repository**
**Operation ID:** `getApiV4ProjectsIdSnapshot`

This feature was introduced in GitLab 10.7

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `wiki` | query | boolean | No | Set to true to receive the wiki repository |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |

