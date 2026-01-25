# invoices_payments_invoice_payment_associated_payment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `charge` | any | No | ID of the successful charge for this payment when `type` is `charge`.Note: charge is only surfaced if the charge object is not associated with a payment intent. If the charge object does have a payment intent, the Invoice Payment surfaces the payment intent instead. |
| `payment_intent` | any | No | ID of the PaymentIntent associated with this payment when `type` is `payment_intent`. Note: This property is only populated for invoices finalized on or after March 15th, 2019. |
| `payment_record` | any | No | ID of the PaymentRecord associated with this payment when `type` is `payment_record`. |
| `type` | enum: charge, payment_intent, payment_record | Yes | Type of payment object associated with this invoice payment. |

