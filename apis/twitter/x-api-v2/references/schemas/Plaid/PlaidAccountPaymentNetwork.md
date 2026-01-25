# PlaidAccountPaymentNetwork

Payment network details associated with the account.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bankId` | string | Yes | The bank ID associated with the account. |
| `identifier` | string | Yes | The payment network identifier. |
| `transferIn` | boolean | Yes | Indicates if transfers into the account are supported. |
| `transferOut` | boolean | Yes | Indicates if transfers out of the account are supported. |
| `type` | string | Yes | The type of payment network (e.g., ACH, SEPA). |

