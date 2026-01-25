# GET /orgs/{org}/actions/runners

**Resource:** [actions](../resources/actions.md)
**List self-hosted runners for an organization**
**Operation ID:** `actions/list-self-hosted-runners-for-org`

Lists all self-hosted runners configured in an organization.

Authenticated users must have admin access to the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint. If the repository is private, the `repo` scope is also required.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string | No | The name of a self-hosted runner. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

