# AuditLogEventDetails

Event specific details. The schema will vary depending on the `event_type`.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `old_value` | string | No | The previous value of the field that was modified in the audited event. |
| `new_value` | string | No | The new value after the modification in the audited event. |
| `group` | object | No | The division or organizational unit where the event occurred. Primarily used to scope role change events (e.g., `user_division_admin_role_changed`), but may appear in other contexts involving group-level changes. |
| `saml_response` | string | No | The response received from the IdP when a user logs in with SAML SSO. Present on `user_login_failed` and `user_login_succeeded` events. |

