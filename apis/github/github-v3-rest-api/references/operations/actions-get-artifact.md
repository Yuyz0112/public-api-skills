# GET /repos/{owner}/{repo}/actions/artifacts/{artifact_id}

**Resource:** [actions](../resources/actions.md)
**Get an artifact**
**Operation ID:** `actions/get-artifact`

Gets a specific artifact for a workflow run.

Anyone with read access to the repository can use this endpoint.

If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[artifact](../schemas/artifact/artifact.md)

