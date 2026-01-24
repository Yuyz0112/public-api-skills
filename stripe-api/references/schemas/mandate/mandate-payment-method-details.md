# mandate_payment_method_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `acss_debit` | [mandate_acss_debit](mandate-acss-debit.md) | No |  |
| `amazon_pay` | [mandate_amazon_pay](mandate-amazon-pay.md) | No |  |
| `au_becs_debit` | [mandate_au_becs_debit](mandate-au-becs-debit.md) | No |  |
| `bacs_debit` | [mandate_bacs_debit](mandate-bacs-debit.md) | No |  |
| `card` | [card_mandate_payment_method_details](card-mandate-payment-method-details.md) | No |  |
| `cashapp` | [mandate_cashapp](mandate-cashapp.md) | No |  |
| `kakao_pay` | [mandate_kakao_pay](mandate-kakao-pay.md) | No |  |
| `klarna` | [mandate_klarna](mandate-klarna.md) | No |  |
| `kr_card` | [mandate_kr_card](mandate-kr-card.md) | No |  |
| `link` | [mandate_link](mandate-link.md) | No |  |
| `naver_pay` | [mandate_naver_pay](mandate-naver-pay.md) | No |  |
| `nz_bank_account` | [mandate_nz_bank_account](mandate-nz-bank-account.md) | No |  |
| `paypal` | [mandate_paypal](mandate-paypal.md) | No |  |
| `payto` | [mandate_payto](mandate-payto.md) | No |  |
| `revolut_pay` | [mandate_revolut_pay](mandate-revolut-pay.md) | No |  |
| `sepa_debit` | [mandate_sepa_debit](mandate-sepa-debit.md) | No |  |
| `type` | string | Yes | This mandate corresponds with a specific payment method type. The `payment_method_details` includes an additional hash with the same name and contains mandate information that's specific to that payment method. |
| `us_bank_account` | [mandate_us_bank_account](mandate-us-bank-account.md) | No |  |

