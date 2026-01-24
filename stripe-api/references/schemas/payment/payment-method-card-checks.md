# payment_method_card_checks

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `address_line1_check` | string | No | If a address line1 was provided, results of the check, one of `pass`, `fail`, `unavailable`, or `unchecked`. |
| `address_postal_code_check` | string | No | If a address postal code was provided, results of the check, one of `pass`, `fail`, `unavailable`, or `unchecked`. |
| `cvc_check` | string | No | If a CVC was provided, results of the check, one of `pass`, `fail`, `unavailable`, or `unchecked`. |

