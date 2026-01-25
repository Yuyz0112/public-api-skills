# GET /rest/api/3/dashboard/{dashboardId}/items/{itemId}/properties/{propertyKey}

**Resource:** [Dashboards](../resources/Dashboards.md)
**Get dashboard item property**
**Operation ID:** `getDashboardItemProperty`

Returns the key and value of a dashboard item property.

A dashboard item enables an app to add user-specific information to a user dashboard. Dashboard items are exposed to users as gadgets that users can add to their dashboards. For more information on how users do this, see [Adding and customizing gadgets](https://confluence.atlassian.com/x/7AeiLQ).

When an app creates a dashboard item it registers a callback to receive the dashboard item ID. The callback fires whenever the item is rendered or, where the item is configurable, the user edits the item. The app then uses this resource to store the item's content or configuration details. For more information on working with dashboard items, see [ Building a dashboard item for a JIRA Connect add-on](https://developer.atlassian.com/server/jira/platform/guide-building-a-dashboard-item-for-a-jira-connect-add-on-33746254/) and the [Dashboard Item](https://developer.atlassian.com/cloud/jira/platform/modules/dashboard-item/) documentation.

There is no resource to set or get dashboard items.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** The user must have read permission of the dashboard or have the dashboard shared with them.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dashboardId` | path | string | Yes | The ID of the dashboard. |
| `itemId` | path | string | Yes | The ID of the dashboard item. |
| `propertyKey` | path | string | Yes | The key of the dashboard item property. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the dashboard, the dashboard item, or dashboard item property is not found, or the dashboard is not owned by or shared with the user. |

**Success Response Schema:**

[EntityProperty](../schemas/Entity/EntityProperty.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
