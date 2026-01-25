# GET /repos/{owner}/{repo}/issues/events/{event_id}

**Resource:** [issues](../resources/issues.md)
**Get an issue event**
**Operation ID:** `issues/get-event`

Gets a single event by the event id.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `event_id` | path | integer | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 410 | (reference) |

**Success Response Schema:**

[issue-event](../schemas/issue-event/issue-event.md)

