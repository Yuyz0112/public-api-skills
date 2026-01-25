# GET /apps.permissions.users.request

**Resource:** [apps.permissions.users](../resources/apps-permissions-users.md)
**Operation ID:** `apps_permissions_users_request`

Enables an app to trigger a permissions modal to grant an app access to a user access scope.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `none` |
| `scopes` | query | string | Yes | A comma separated list of user scopes to request for |
| `trigger_id` | query | string | Yes | Token used to trigger the request |
| `user` | query | string | Yes | The user this scope is being requested for |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Standard success response when used with a user token |
| default | Standard failure response when trigger_id is invalid |

## Security

- **slackAuth**: none
