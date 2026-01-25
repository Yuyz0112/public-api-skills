# payments_primitives_payment_records_resource_payment_method_details

Details about the Payment Method used in this payment attempt.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ach_credit_transfer` | [payment_method_details_ach_credit_transfer](payment-method-details-ach-credit-transfer.md) | No |  |
| `ach_debit` | [payment_method_details_ach_debit](payment-method-details-ach-debit.md) | No |  |
| `acss_debit` | [payment_method_details_acss_debit](payment-method-details-acss-debit.md) | No |  |
| `affirm` | [payment_method_details_affirm](payment-method-details-affirm.md) | No |  |
| `afterpay_clearpay` | [payment_method_details_afterpay_clearpay](payment-method-details-afterpay-clearpay.md) | No |  |
| `alipay` | [payment_flows_private_payment_methods_alipay_details](payment-flows-private-payment-methods-alipay-details.md) | No |  |
| `alma` | [payment_method_details_alma](payment-method-details-alma.md) | No |  |
| `amazon_pay` | [payment_method_details_amazon_pay](payment-method-details-amazon-pay.md) | No |  |
| `au_becs_debit` | [payment_method_details_au_becs_debit](payment-method-details-au-becs-debit.md) | No |  |
| `bacs_debit` | [payment_method_details_bacs_debit](payment-method-details-bacs-debit.md) | No |  |
| `bancontact` | [payment_method_details_bancontact](payment-method-details-bancontact.md) | No |  |
| `billie` | [payment_method_details_billie](payment-method-details-billie.md) | No |  |
| `billing_details` | any | No | The billing details associated with the method of payment. |
| `blik` | [payment_method_details_blik](payment-method-details-blik.md) | No |  |
| `boleto` | [payment_method_details_boleto](payment-method-details-boleto.md) | No |  |
| `card` | [payments_primitives_payment_records_resource_payment_method_card_details](payments-primitives-payment-records-resource-payment-method-card-details.md) | No |  |
| `card_present` | [payment_method_details_card_present](payment-method-details-card-present.md) | No |  |
| `cashapp` | [payment_method_details_cashapp](payment-method-details-cashapp.md) | No |  |
| `crypto` | [payment_method_details_crypto](payment-method-details-crypto.md) | No |  |
| `custom` | [payments_primitives_payment_records_resource_payment_method_custom_details](payments-primitives-payment-records-resource-payment-method-custom-details.md) | No |  |
| `customer_balance` | [payment_method_details_customer_balance](payment-method-details-customer-balance.md) | No |  |
| `eps` | [payment_method_details_eps](payment-method-details-eps.md) | No |  |
| `fpx` | [payment_method_details_fpx](payment-method-details-fpx.md) | No |  |
| `giropay` | [payment_method_details_giropay](payment-method-details-giropay.md) | No |  |
| `grabpay` | [payment_method_details_grabpay](payment-method-details-grabpay.md) | No |  |
| `ideal` | [payment_method_details_ideal](payment-method-details-ideal.md) | No |  |
| `interac_present` | [payment_method_details_interac_present](payment-method-details-interac-present.md) | No |  |
| `kakao_pay` | [payment_method_details_kakao_pay](payment-method-details-kakao-pay.md) | No |  |
| `klarna` | [payment_method_details_klarna](payment-method-details-klarna.md) | No |  |
| `konbini` | [payment_method_details_konbini](payment-method-details-konbini.md) | No |  |
| `kr_card` | [payment_method_details_kr_card](payment-method-details-kr-card.md) | No |  |
| `link` | [payment_method_details_link](payment-method-details-link.md) | No |  |
| `mb_way` | [payment_method_details_payment_record_mb_way](payment-method-details-payment-record-mb-way.md) | No |  |
| `mobilepay` | [payment_method_details_mobilepay](payment-method-details-mobilepay.md) | No |  |
| `multibanco` | [payment_method_details_multibanco](payment-method-details-multibanco.md) | No |  |
| `naver_pay` | [payment_method_details_naver_pay](payment-method-details-naver-pay.md) | No |  |
| `nz_bank_account` | [payment_method_details_nz_bank_account](payment-method-details-nz-bank-account.md) | No |  |
| `oxxo` | [payment_method_details_oxxo](payment-method-details-oxxo.md) | No |  |
| `p24` | [payment_method_details_p24](payment-method-details-p24.md) | No |  |
| `pay_by_bank` | [payment_method_details_pay_by_bank](payment-method-details-pay-by-bank.md) | No |  |
| `payco` | [payment_method_details_payco](payment-method-details-payco.md) | No |  |
| `payment_method` | string | No | ID of the Stripe PaymentMethod used to make this payment. |
| `paynow` | [payment_method_details_paynow](payment-method-details-paynow.md) | No |  |
| `paypal` | [payment_method_details_paypal](payment-method-details-paypal.md) | No |  |
| `payto` | [payment_method_details_payto](payment-method-details-payto.md) | No |  |
| `pix` | [payment_method_details_pix](payment-method-details-pix.md) | No |  |
| `promptpay` | [payment_method_details_promptpay](payment-method-details-promptpay.md) | No |  |
| `revolut_pay` | [payment_method_details_revolut_pay](payment-method-details-revolut-pay.md) | No |  |
| `samsung_pay` | [payment_method_details_samsung_pay](payment-method-details-samsung-pay.md) | No |  |
| `satispay` | [payment_method_details_satispay](payment-method-details-satispay.md) | No |  |
| `sepa_debit` | [payment_method_details_sepa_debit](payment-method-details-sepa-debit.md) | No |  |
| `sofort` | [payment_method_details_sofort](payment-method-details-sofort.md) | No |  |
| `stripe_account` | [payment_method_details_stripe_account](payment-method-details-stripe-account.md) | No |  |
| `swish` | [payment_method_details_swish](payment-method-details-swish.md) | No |  |
| `twint` | [payment_method_details_twint](payment-method-details-twint.md) | No |  |
| `type` | string | Yes | The type of transaction-specific details of the payment method used in the payment. See [PaymentMethod.type](https://docs.stripe.com/api/payment_methods/object#payment_method_object-type) for the full list of possible types.
An additional hash is included on `payment_method_details` with a name matching this value.
It contains information specific to the payment method. |
| `us_bank_account` | [payment_method_details_payment_record_us_bank_account](payment-method-details-payment-record-us-bank-account.md) | No |  |
| `wechat` | [payment_method_details_wechat](payment-method-details-wechat.md) | No |  |
| `wechat_pay` | [payment_method_details_wechat_pay](payment-method-details-wechat-pay.md) | No |  |
| `zip` | [payment_method_details_payment_record_zip](payment-method-details-payment-record-zip.md) | No |  |

