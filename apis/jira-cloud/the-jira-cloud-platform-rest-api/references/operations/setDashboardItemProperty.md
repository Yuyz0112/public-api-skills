# PUT /rest/api/3/dashboard/{dashboardId}/items/{itemId}/properties/{propertyKey}

**Resource:** [Dashboards](../resources/Dashboards.md)
**Set dashboard item property**
**Operation ID:** `setDashboardItemProperty`

Sets the value of a dashboard item property. Use this resource in apps to store custom data against a dashboard item.

A dashboard item enables an app to add user-specific information to a user dashboard. Dashboard items are exposed to users as gadgets that users can add to their dashboards. For more information on how users do this, see [Adding and customizing gadgets](https://confluence.atlassian.com/x/7AeiLQ).

When an app creates a dashboard item it registers a callback to receive the dashboard item ID. The callback fires whenever the item is rendered or, where the item is configurable, the user edits the item. The app then uses this resource to store the item's content or configuration details. For more information on working with dashboard items, see [ Building a dashboard item for a JIRA Connect add-on](https://developer.atlassian.com/server/jira/platform/guide-building-a-dashboard-item-for-a-jira-connect-add-on-33746254/) and the [Dashboard Item](https://developer.atlassian.com/cloud/jira/platform/modules/dashboard-item/) documentation.

There is no resource to set or get dashboard items.

The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON blob. The maximum length is 32768 characters.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** The user must have edit permisson of the dashboard.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dashboardId` | path | string | Yes | The ID of the dashboard. |
| `itemId` | path | string | Yes | The ID of the dashboard item. |
| `propertyKey` | path | string | Yes | The key of the dashboard item property. The maximum length is 255 characters. For dashboard items with a spec URI and no complete module key, if the provided propertyKey is equal to "config", the request body's JSON must be an object with all keys and values as strings. |

## Request Body

The value of the property. The value has to be a valid, non-empty [JSON](https://tools.ietf.org/html/rfc4627) value. The maximum length of the property value is 32768 bytes.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the dashboard item property is updated. |
| 201 | Returned if the dashboard item property is created. |
| 400 | Returned if:

 *  Request is invalid
 *  Or if all of these conditions are met in the request:
    
     *  The dashboard item has a spec URI and no complete module key
     *  The value of propertyKey is equal to "config"
     *  The request body contains a JSON object whose keys and values are not strings. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user is not the owner of the dashboard. |
| 404 | Returned if the dashboard item is not found or the dashboard is not shared with the user. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
