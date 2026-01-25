# PUT /repos/{owner}/{repo}/actions/workflows/{workflow_id}/disable

**Resource:** [actions](../resources/actions.md)
**Disable a workflow**
**Operation ID:** `actions/disable-workflow`

Disables a workflow and sets the `state` of the workflow to `disabled_manually`. You can replace `workflow_id` with the workflow file name. For example, you could use `main.yaml`.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

