# DELETE /api/v4/groups/{id}/epics/{epic_iid}/related_epics/{related_epic_link_id}

**Resource:** [Epics](../resources/Epics.md)
**Remove epics relation**
**Operation ID:** `deleteApiV4GroupsIdEpicsEpicIidRelatedEpicsRelatedEpicLinkId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | ID or URL-encoded path of the group |
| `related_epic_link_id` | path | integer | Yes | Internal ID of a related epic link |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

