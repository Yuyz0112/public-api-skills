# GET /repos/{owner}/{repo}/actions/workflows/{workflow_id}

**Resource:** [actions](../resources/actions.md)
**Get a workflow**
**Operation ID:** `actions/get-workflow`

Gets a specific workflow. You can replace `workflow_id` with the workflow
file name. For example, you could use `main.yaml`.

Anyone with read access to the repository can use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint with a private repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[workflow](../schemas/workflow/workflow.md)

