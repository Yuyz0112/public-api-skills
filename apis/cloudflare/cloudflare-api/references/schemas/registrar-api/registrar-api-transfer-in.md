# registrar-api_transfer_in

Statuses for domain transfers into Cloudflare Registrar.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accept_foa` | enum: needed, ok | No | Form of authorization has been accepted by the registrant. |
| `approve_transfer` | enum: needed, ok, pending... | No | Shows transfer status with the registry. |
| `can_cancel_transfer` | boolean | No | Indicates if cancellation is still possible. |
| `disable_privacy` | enum: needed, ok, unknown | No | Privacy guards are disabled at the foreign registrar. |
| `enter_auth_code` | enum: needed, ok, pending... | No | Auth code has been entered and verified. |
| `unlock_domain` | enum: needed, ok, pending... | No | Domain is unlocked at the foreign registrar. |

