# payment_method_us_bank_account

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_holder_type` | enum: company, individual | No | Account holder type: individual or company. |
| `account_type` | enum: checking, savings | No | Account type: checkings or savings. Defaults to checking if omitted. |
| `bank_name` | string | No | The name of the bank. |
| `financial_connections_account` | string | No | The ID of the Financial Connections Account used to create the payment method. |
| `fingerprint` | string | No | Uniquely identifies this particular bank account. You can use this attribute to check whether two bank accounts are the same. |
| `last4` | string | No | Last four digits of the bank account number. |
| `networks` | any | No | Contains information about US bank account networks that can be used. |
| `routing_number` | string | No | Routing number of the bank account. |
| `status_details` | any | No | Contains information about the future reusability of this PaymentMethod. |

