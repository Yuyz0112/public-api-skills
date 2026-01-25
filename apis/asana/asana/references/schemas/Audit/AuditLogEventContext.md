# AuditLogEventContext

The context from which this event originated.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `context_type` | enum: web, desktop, mobile... | No | The type of context.
Can be one of `web`, `desktop`, `mobile`, `asana_support`, `asana`, `email`, or `api`. |
| `api_authentication_method` | enum: cookie, oauth, personal_access_token... | No | The authentication method used in the context of an API request.
Only present if the `context_type` is `api`. Can be one of `cookie`, `oauth`, `personal_access_token`, or `service_account`. |
| `client_ip_address` | string | No | The IP address of the client that initiated the event, if applicable. |
| `user_agent` | string | No | The user agent of the client that initiated the event, if applicable. |
| `oauth_app_name` | string | No | The name of the OAuth App that initiated the event.
Only present if the `api_authentication_method` is `oauth`. |
| `rule_name` | string | No | The name of the automation rule that initiated the event. |
| `on_behalf_of_user_id` | integer | No | The ID of the user who requested a change via support. |

