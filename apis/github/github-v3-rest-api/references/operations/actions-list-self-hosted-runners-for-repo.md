# GET /repos/{owner}/{repo}/actions/runners

**Resource:** [actions](../resources/actions.md)
**List self-hosted runners for a repository**
**Operation ID:** `actions/list-self-hosted-runners-for-repo`

Lists all self-hosted runners configured in a repository.

Authenticated users must have admin access to the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string | No | The name of a self-hosted runner. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

