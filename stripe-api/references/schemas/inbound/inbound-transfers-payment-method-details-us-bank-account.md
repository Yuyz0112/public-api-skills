# inbound_transfers_payment_method_details_us_bank_account

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_holder_type` | enum: company, individual | No | Account holder type: individual or company. |
| `account_type` | enum: checking, savings | No | Account type: checkings or savings. Defaults to checking if omitted. |
| `bank_name` | string | No | Name of the bank associated with the bank account. |
| `fingerprint` | string | No | Uniquely identifies this particular bank account. You can use this attribute to check whether two bank accounts are the same. |
| `last4` | string | No | Last four digits of the bank account number. |
| `mandate` | any | No | ID of the mandate used to make this payment. |
| `network` | enum: ach | Yes | The network rails used. See the [docs](https://docs.stripe.com/treasury/money-movement/timelines) to learn more about money movement timelines for each network type. |
| `routing_number` | string | No | Routing number of the bank account. |

