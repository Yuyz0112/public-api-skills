# GET /app/installation-requests

**Resource:** [apps](../resources/apps.md)
**List installation requests for the authenticated app**
**Operation ID:** `apps/list-installation-requests-for-authenticated-app`

Lists all the pending installation requests for the authenticated GitHub App.

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of integration installation requests |
| 304 | (reference) |
| 401 | (reference) |

**Success Response Schema:**

Array of [integration-installation-request](../schemas/integration-installation-request/integration-installation-request.md)

