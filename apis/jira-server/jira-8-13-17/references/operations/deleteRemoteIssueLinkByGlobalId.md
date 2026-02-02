# DELETE /issue/{issueIdOrKey}/remotelink

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `deleteRemoteIssueLinkByGlobalId`

Delete the remote issue link with the given global id on the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `globalId` | query | string | No | the global id of the remote issue link |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

