# GET /repos/{owner}/{repo}/actions/runners/downloads

**Resource:** [actions](../resources/actions.md)
**List runner applications for a repository**
**Operation ID:** `actions/list-runner-applications-for-repo`

Lists binaries for the runner application that you can download and run.

Authenticated users must have admin access to the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [runner-application](../schemas/runner-application/runner-application.md)

