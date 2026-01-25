# GET /v1/payments

**Resource:** [Payments](../resources/Payments.md)
**Get payments**
**Operation ID:** `getPayments`

There are two methods to query for a user's payment information on a plugin, widget, or Community file. The first method, using plugin payment tokens, is typically used when making queries from a plugin's or widget's code. The second method, providing a user ID and resource ID, is typically used when making queries from anywhere else.

Note that you can only query for resources that you own. In most cases, this means that you can only query resources that you originally created.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `plugin_payment_token` | query | string | No | Short-lived token returned from "getPluginPaymentTokenAsync" in the plugin payments API and used to authenticate to this endpoint. Read more about generating this token through "Calling the Payments REST API from a plugin or widget" below. |
| `user_id` | query | string | No | The ID of the user to query payment information about. You can get the user ID by having the user OAuth2 to the Figma REST API. |
| `community_file_id` | query | string | No | The ID of the Community file to query a user's payment information on. You can get the Community file ID from the file's Community page (look for the number after "file/" in the URL). Provide exactly one of "community_file_id", "plugin_id", or "widget_id". |
| `plugin_id` | query | string | No | The ID of the plugin to query a user's payment information on. You can get the plugin ID from the plugin's manifest, or from the plugin's Community page (look for the number after "plugin/" in the URL). Provide exactly one of "community_file_id", "plugin_id", or "widget_id". |
| `widget_id` | query | string | No | The ID of the widget to query a user's payment information on. You can get the widget ID from the widget's manifest, or from the widget's Community page (look for the number after "widget/" in the URL). Provide exactly one of "community_file_id", "plugin_id", or "widget_id". |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 401 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
