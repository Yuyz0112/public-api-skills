# GET /notificationscheme

**Resource:** [notificationscheme](../resources/notificationscheme.md)
**Operation ID:** `getNotificationSchemes`

Returns a <a href="#pagination">paginated</a> list of notification schemes. In order to access notification scheme, the calling user is
 required to have permissions to administer at least one project associated with the requested notification scheme. Each scheme contains
 a list of events and recipient configured to receive notifications for these events. Consumer should allow events without recipients to appear in response.
 The list is ordered by the scheme's name.
 Follow the documentation of /notificationscheme/{id} resource for all details about returned value.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | the index of the first notification scheme to return (0 based). |
| `maxResults` | query | integer (int32) | No | the maximum number of notification schemes to return (max 50). |
| `expand` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

