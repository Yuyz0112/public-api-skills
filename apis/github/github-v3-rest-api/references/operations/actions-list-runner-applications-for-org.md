# GET /orgs/{org}/actions/runners/downloads

**Resource:** [actions](../resources/actions.md)
**List runner applications for an organization**
**Operation ID:** `actions/list-runner-applications-for-org`

Lists binaries for the runner application that you can download and run.

Authenticated users must have admin access to the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.  If the repository is private, the `repo` scope is also required.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [runner-application](../schemas/runner-application/runner-application.md)

