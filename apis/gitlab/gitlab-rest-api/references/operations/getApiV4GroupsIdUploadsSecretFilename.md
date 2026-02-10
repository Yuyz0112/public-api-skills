# GET /api/v4/groups/{id}/uploads/{secret}/{filename}

**Resource:** [Groups](../resources/Groups.md)
**Download a single project upload by secret and filename**
**Operation ID:** `getApiV4GroupsIdUploadsSecretFilename`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `secret` | path | string | Yes | The 32-character secret of a group upload |
| `filename` | path | string | Yes | The filename of a group upload |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Unauthenticated |
| 404 | Not found |

