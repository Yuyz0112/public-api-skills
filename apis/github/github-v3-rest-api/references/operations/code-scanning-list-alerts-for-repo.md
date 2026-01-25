# GET /repos/{owner}/{repo}/code-scanning/alerts

**Resource:** [code-scanning](../resources/code-scanning.md)
**List code scanning alerts for a repository**
**Operation ID:** `code-scanning/list-alerts-for-repo`

Lists code scanning alerts.

The response includes a `most_recent_instance` object.
This provides details of the most recent instance of this alert
for the default branch (or for the specified Git reference if you used `ref` in the request).

OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `sort` | query | enum: created, updated | No | The property by which to sort the results. |
| `state` | query | code-scanning-alert-state-query | No | If specified, only code scanning alerts with this state will be returned. |
| `severity` | query | code-scanning-alert-severity | No | If specified, only code scanning alerts with this severity will be returned. |
| `assignees` | query | string | No | Filter alerts by assignees. Provide a comma-separated list of user handles (e.g., `octocat` or `octocat,hubot`).
Use `*` to list alerts with at least one assignee or `none` to list alerts with no assignees.
 |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

Array of [code-scanning-alert-items](../schemas/code-scanning-alert-items/code-scanning-alert-items.md)

