# dispute_payment_method_details_card

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `brand` | string | Yes | Card brand. Can be `amex`, `cartes_bancaires`, `diners`, `discover`, `eftpos_au`, `jcb`, `link`, `mastercard`, `unionpay`, `visa` or `unknown`. |
| `case_type` | enum: block, chargeback, compliance... | Yes | The type of dispute opened. Different case types may have varying fees and financial impact. |
| `network_reason_code` | string | No | The card network's specific dispute reason code, which maps to one of Stripe's primary dispute categories to simplify response guidance. The [Network code map](https://stripe.com/docs/disputes/categories#network-code-map) lists all available dispute reason codes by network. |

