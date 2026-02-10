# PUT /api/v4/groups/{id}/members/{member_id}/approve

**Resource:** [Members](../resources/Members.md)
**Approves a pending member**
**Operation ID:** `putApiV4GroupsIdMembersMemberIdApprove`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `member_id` | path | integer | Yes | The ID of the member requiring approval |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

