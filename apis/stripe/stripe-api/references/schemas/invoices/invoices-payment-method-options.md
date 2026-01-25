# invoices_payment_method_options

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `acss_debit` | any | No | If paying by `acss_debit`, this sub-hash contains details about the Canadian pre-authorized debit payment method options to pass to the invoice’s PaymentIntent. |
| `bancontact` | any | No | If paying by `bancontact`, this sub-hash contains details about the Bancontact payment method options to pass to the invoice’s PaymentIntent. |
| `card` | any | No | If paying by `card`, this sub-hash contains details about the Card payment method options to pass to the invoice’s PaymentIntent. |
| `customer_balance` | any | No | If paying by `customer_balance`, this sub-hash contains details about the Bank transfer payment method options to pass to the invoice’s PaymentIntent. |
| `konbini` | any | No | If paying by `konbini`, this sub-hash contains details about the Konbini payment method options to pass to the invoice’s PaymentIntent. |
| `payto` | any | No | If paying by `payto`, this sub-hash contains details about the PayTo payment method options to pass to the invoice’s PaymentIntent. |
| `sepa_debit` | any | No | If paying by `sepa_debit`, this sub-hash contains details about the SEPA Direct Debit payment method options to pass to the invoice’s PaymentIntent. |
| `us_bank_account` | any | No | If paying by `us_bank_account`, this sub-hash contains details about the ACH direct debit payment method options to pass to the invoice’s PaymentIntent. |

