# PlaidAccountContact

Contact information associated with a Plaid account.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `addresses` | PlaidAddress[] | Yes | List of addresses associated with the account holder. |
| `emails` | string[] | Yes | List of email addresses associated with the account holder. |
| `name` | [PlaidName](PlaidName.md) | Yes |  |
| `relationship` | string | No | Relationship of the contact to the account. |
| `telephones` | PlaidTelephone[] | Yes | List of telephone numbers associated with the account holder. |

