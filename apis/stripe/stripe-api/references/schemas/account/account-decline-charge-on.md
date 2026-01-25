# account_decline_charge_on

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avs_failure` | boolean | Yes | Whether Stripe automatically declines charges with an incorrect ZIP or postal code. This setting only applies when a ZIP or postal code is provided and they fail bank verification. |
| `cvc_failure` | boolean | Yes | Whether Stripe automatically declines charges with an incorrect CVC. This setting only applies when a CVC is provided and it fails bank verification. |

