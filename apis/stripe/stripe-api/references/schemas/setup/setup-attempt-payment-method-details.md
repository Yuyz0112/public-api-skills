# setup_attempt_payment_method_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `acss_debit` | [setup_attempt_payment_method_details_acss_debit](setup-attempt-payment-method-details-acss-debit.md) | No |  |
| `amazon_pay` | [setup_attempt_payment_method_details_amazon_pay](setup-attempt-payment-method-details-amazon-pay.md) | No |  |
| `au_becs_debit` | [setup_attempt_payment_method_details_au_becs_debit](setup-attempt-payment-method-details-au-becs-debit.md) | No |  |
| `bacs_debit` | [setup_attempt_payment_method_details_bacs_debit](setup-attempt-payment-method-details-bacs-debit.md) | No |  |
| `bancontact` | [setup_attempt_payment_method_details_bancontact](setup-attempt-payment-method-details-bancontact.md) | No |  |
| `boleto` | [setup_attempt_payment_method_details_boleto](setup-attempt-payment-method-details-boleto.md) | No |  |
| `card` | [setup_attempt_payment_method_details_card](setup-attempt-payment-method-details-card.md) | No |  |
| `card_present` | [setup_attempt_payment_method_details_card_present](setup-attempt-payment-method-details-card-present.md) | No |  |
| `cashapp` | [setup_attempt_payment_method_details_cashapp](setup-attempt-payment-method-details-cashapp.md) | No |  |
| `ideal` | [setup_attempt_payment_method_details_ideal](setup-attempt-payment-method-details-ideal.md) | No |  |
| `kakao_pay` | [setup_attempt_payment_method_details_kakao_pay](setup-attempt-payment-method-details-kakao-pay.md) | No |  |
| `klarna` | [setup_attempt_payment_method_details_klarna](setup-attempt-payment-method-details-klarna.md) | No |  |
| `kr_card` | [setup_attempt_payment_method_details_kr_card](setup-attempt-payment-method-details-kr-card.md) | No |  |
| `link` | [setup_attempt_payment_method_details_link](setup-attempt-payment-method-details-link.md) | No |  |
| `naver_pay` | [setup_attempt_payment_method_details_naver_pay](setup-attempt-payment-method-details-naver-pay.md) | No |  |
| `nz_bank_account` | [setup_attempt_payment_method_details_nz_bank_account](setup-attempt-payment-method-details-nz-bank-account.md) | No |  |
| `paypal` | [setup_attempt_payment_method_details_paypal](setup-attempt-payment-method-details-paypal.md) | No |  |
| `payto` | [setup_attempt_payment_method_details_payto](setup-attempt-payment-method-details-payto.md) | No |  |
| `revolut_pay` | [setup_attempt_payment_method_details_revolut_pay](setup-attempt-payment-method-details-revolut-pay.md) | No |  |
| `sepa_debit` | [setup_attempt_payment_method_details_sepa_debit](setup-attempt-payment-method-details-sepa-debit.md) | No |  |
| `sofort` | [setup_attempt_payment_method_details_sofort](setup-attempt-payment-method-details-sofort.md) | No |  |
| `type` | string | Yes | The type of the payment method used in the SetupIntent (e.g., `card`). An additional hash is included on `payment_method_details` with a name matching this value. It contains confirmation-specific information for the payment method. |
| `us_bank_account` | [setup_attempt_payment_method_details_us_bank_account](setup-attempt-payment-method-details-us-bank-account.md) | No |  |

