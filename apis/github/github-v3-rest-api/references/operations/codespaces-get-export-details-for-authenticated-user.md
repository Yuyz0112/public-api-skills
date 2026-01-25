# GET /user/codespaces/{codespace_name}/exports/{export_id}

**Resource:** [codespaces](../resources/codespaces.md)
**Get details about a codespace export**
**Operation ID:** `codespaces/get-export-details-for-authenticated-user`

Gets information about an export of a codespace.

OAuth app tokens and personal access tokens (classic) need the `codespace` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[codespace-export-details](../schemas/codespace-export-details/codespace-export-details.md)

