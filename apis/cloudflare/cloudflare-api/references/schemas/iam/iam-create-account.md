# iam_create-account

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Account name |
| `type` | [iam_account-type](iam-account-type.md) | No |  |
| `unit` | object | No | information related to the tenant unit, and optionally, an id of the unit to create the account on. see https://developers.cloudflare.com/tenant/how-to/manage-accounts/ |

## Nested Fields

### `unit`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | Tenant unit ID |

