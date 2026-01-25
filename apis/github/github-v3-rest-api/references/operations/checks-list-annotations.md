# GET /repos/{owner}/{repo}/check-runs/{check_run_id}/annotations

**Resource:** [checks](../resources/checks.md)
**List check run annotations**
**Operation ID:** `checks/list-annotations`

Lists annotations for a check run using the annotation `id`.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint on a private repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [check-annotation](../schemas/check-annotation/check-annotation.md)

