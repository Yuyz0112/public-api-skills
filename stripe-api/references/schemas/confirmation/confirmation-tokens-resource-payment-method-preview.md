# confirmation_tokens_resource_payment_method_preview

Details of the PaymentMethod collected by Payment Element

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `acss_debit` | [payment_method_acss_debit](payment-method-acss-debit.md) | No |  |
| `affirm` | [payment_method_affirm](payment-method-affirm.md) | No |  |
| `afterpay_clearpay` | [payment_method_afterpay_clearpay](payment-method-afterpay-clearpay.md) | No |  |
| `alipay` | [payment_flows_private_payment_methods_alipay](payment-flows-private-payment-methods-alipay.md) | No |  |
| `allow_redisplay` | enum: always, limited, unspecified | No | This field indicates whether this payment method can be shown again to its customer in a checkout flow. Stripe products such as Checkout and Elements use this field to determine whether a payment method can be shown as a saved payment method in a checkout flow. The field defaults to “unspecified”. |
| `alma` | [payment_method_alma](payment-method-alma.md) | No |  |
| `amazon_pay` | [payment_method_amazon_pay](payment-method-amazon-pay.md) | No |  |
| `au_becs_debit` | [payment_method_au_becs_debit](payment-method-au-becs-debit.md) | No |  |
| `bacs_debit` | [payment_method_bacs_debit](payment-method-bacs-debit.md) | No |  |
| `bancontact` | [payment_method_bancontact](payment-method-bancontact.md) | No |  |
| `billie` | [payment_method_billie](payment-method-billie.md) | No |  |
| `billing_details` | [billing_details](billing-details.md) | Yes |  |
| `blik` | [payment_method_blik](payment-method-blik.md) | No |  |
| `boleto` | [payment_method_boleto](payment-method-boleto.md) | No |  |
| `card` | [payment_method_card](payment-method-card.md) | No |  |
| `card_present` | [payment_method_card_present](payment-method-card-present.md) | No |  |
| `cashapp` | [payment_method_cashapp](payment-method-cashapp.md) | No |  |
| `crypto` | [payment_method_crypto](payment-method-crypto.md) | No |  |
| `customer` | any | No | The ID of the Customer to which this PaymentMethod is saved. This will not be set when the PaymentMethod has not been saved to a Customer. |
| `customer_account` | string | No |  |
| `customer_balance` | [payment_method_customer_balance](payment-method-customer-balance.md) | No |  |
| `eps` | [payment_method_eps](payment-method-eps.md) | No |  |
| `fpx` | [payment_method_fpx](payment-method-fpx.md) | No |  |
| `giropay` | [payment_method_giropay](payment-method-giropay.md) | No |  |
| `grabpay` | [payment_method_grabpay](payment-method-grabpay.md) | No |  |
| `ideal` | [payment_method_ideal](payment-method-ideal.md) | No |  |
| `interac_present` | [payment_method_interac_present](payment-method-interac-present.md) | No |  |
| `kakao_pay` | [payment_method_kakao_pay](payment-method-kakao-pay.md) | No |  |
| `klarna` | [payment_method_klarna](payment-method-klarna.md) | No |  |
| `konbini` | [payment_method_konbini](payment-method-konbini.md) | No |  |
| `kr_card` | [payment_method_kr_card](payment-method-kr-card.md) | No |  |
| `link` | [payment_method_link](payment-method-link.md) | No |  |
| `mb_way` | [payment_method_mb_way](payment-method-mb-way.md) | No |  |
| `mobilepay` | [payment_method_mobilepay](payment-method-mobilepay.md) | No |  |
| `multibanco` | [payment_method_multibanco](payment-method-multibanco.md) | No |  |
| `naver_pay` | [payment_method_naver_pay](payment-method-naver-pay.md) | No |  |
| `nz_bank_account` | [payment_method_nz_bank_account](payment-method-nz-bank-account.md) | No |  |
| `oxxo` | [payment_method_oxxo](payment-method-oxxo.md) | No |  |
| `p24` | [payment_method_p24](payment-method-p24.md) | No |  |
| `pay_by_bank` | [payment_method_pay_by_bank](payment-method-pay-by-bank.md) | No |  |
| `payco` | [payment_method_payco](payment-method-payco.md) | No |  |
| `paynow` | [payment_method_paynow](payment-method-paynow.md) | No |  |
| `paypal` | [payment_method_paypal](payment-method-paypal.md) | No |  |
| `payto` | [payment_method_payto](payment-method-payto.md) | No |  |
| `pix` | [payment_method_pix](payment-method-pix.md) | No |  |
| `promptpay` | [payment_method_promptpay](payment-method-promptpay.md) | No |  |
| `revolut_pay` | [payment_method_revolut_pay](payment-method-revolut-pay.md) | No |  |
| `samsung_pay` | [payment_method_samsung_pay](payment-method-samsung-pay.md) | No |  |
| `satispay` | [payment_method_satispay](payment-method-satispay.md) | No |  |
| `sepa_debit` | [payment_method_sepa_debit](payment-method-sepa-debit.md) | No |  |
| `sofort` | [payment_method_sofort](payment-method-sofort.md) | No |  |
| `swish` | [payment_method_swish](payment-method-swish.md) | No |  |
| `twint` | [payment_method_twint](payment-method-twint.md) | No |  |
| `type` | enum: acss_debit, affirm, afterpay_clearpay... | Yes | The type of the PaymentMethod. An additional hash is included on the PaymentMethod with a name matching this value. It contains additional information specific to the PaymentMethod type. |
| `us_bank_account` | [payment_method_us_bank_account](payment-method-us-bank-account.md) | No |  |
| `wechat_pay` | [payment_method_wechat_pay](payment-method-wechat-pay.md) | No |  |
| `zip` | [payment_method_zip](payment-method-zip.md) | No |  |

