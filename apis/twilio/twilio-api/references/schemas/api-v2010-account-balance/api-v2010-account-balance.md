# api.v2010.account.balance

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The unique SID identifier of the Account. |
| `balance` | string | No | The balance of the Account, in units specified by the unit parameter. Balance changes may not be reflected immediately. Child accounts do not contain balance information |
| `currency` | string | No | The units of currency for the account balance |

