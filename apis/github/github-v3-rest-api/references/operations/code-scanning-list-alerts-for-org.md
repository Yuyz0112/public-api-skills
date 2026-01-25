# GET /orgs/{org}/code-scanning/alerts

**Resource:** [code-scanning](../resources/code-scanning.md)
**List code scanning alerts for an organization**
**Operation ID:** `code-scanning/list-alerts-for-org`

Lists code scanning alerts for the default branch for all eligible repositories in an organization. Eligible repositories are repositories that are owned by organizations that you own or for which you are a security manager. For more information, see "[Managing security managers in your organization](https://docs.github.com/organizations/managing-peoples-access-to-your-organization-with-roles/managing-security-managers-in-your-organization)."

The authenticated user must be an owner or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `security_events` or `repo`s cope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `state` | query | code-scanning-alert-state-query | No | If specified, only code scanning alerts with this state will be returned. |
| `sort` | query | enum: created, updated | No | The property by which to sort the results. |
| `severity` | query | code-scanning-alert-severity | No | If specified, only code scanning alerts with this severity will be returned. |
| `assignees` | query | string | No | Filter alerts by assignees. Provide a comma-separated list of user handles (e.g., `octocat` or `octocat,hubot`).
Use `*` to list alerts with at least one assignee or `none` to list alerts with no assignees.
 |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

Array of [code-scanning-organization-alert-items](../schemas/code-scanning-organization-alert-items/code-scanning-organization-alert-items.md)

