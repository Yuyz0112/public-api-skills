# payment_method_configuration

PaymentMethodConfigurations control which payment methods are displayed to your customers when you don't explicitly specify payment method types. You can have multiple configurations with different sets of payment methods for different scenarios.

There are two types of PaymentMethodConfigurations. Which is used depends on the [charge type](https://docs.stripe.com/connect/charges):

**Direct** configurations apply to payments created on your account, including Connect destination charges, Connect separate charges and transfers, and payments not involving Connect.

**Child** configurations apply to payments created on your connected accounts using direct charges, and charges with the on_behalf_of parameter.

Child configurations have a `parent` that sets default values and controls which settings connected accounts may override. You can specify a parent ID at payment time, and Stripe will automatically resolve the connected account’s associated child configuration. Parent configurations are [managed in the dashboard](https://dashboard.stripe.com/settings/payment_methods/connected_accounts) and are not available in this API.

Related guides:
- [Payment Method Configurations API](https://docs.stripe.com/connect/payment-method-configurations)
- [Multiple configurations on dynamic payment methods](https://docs.stripe.com/payments/multiple-payment-method-configs)
- [Multiple configurations for your Connect accounts](https://docs.stripe.com/connect/multiple-payment-method-configurations)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `acss_debit` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `active` | boolean | Yes | Whether the configuration can be used for new payments. |
| `affirm` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `afterpay_clearpay` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `alipay` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `alma` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `amazon_pay` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `apple_pay` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `application` | string | No | For child configs, the Connect application associated with the configuration. |
| `au_becs_debit` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `bacs_debit` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `bancontact` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `billie` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `blik` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `boleto` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `card` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `cartes_bancaires` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `cashapp` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `crypto` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `customer_balance` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `eps` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `fpx` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `giropay` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `google_pay` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `grabpay` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `id` | string | Yes | Unique identifier for the object. |
| `ideal` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `is_default` | boolean | Yes | The default configuration is used whenever a payment method configuration is not specified. |
| `jcb` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `kakao_pay` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `klarna` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `konbini` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `kr_card` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `link` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `mb_way` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `mobilepay` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `multibanco` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `name` | string | Yes | The configuration's name. |
| `naver_pay` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `nz_bank_account` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `object` | enum: payment_method_configuration | Yes | String representing the object's type. Objects of the same type share the same value. |
| `oxxo` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `p24` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `parent` | string | No | For child configs, the configuration's parent configuration. |
| `pay_by_bank` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `payco` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `paynow` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `paypal` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `payto` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `pix` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `promptpay` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `revolut_pay` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `samsung_pay` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `satispay` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `sepa_debit` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `sofort` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `swish` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `twint` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `us_bank_account` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `wechat_pay` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |
| `zip` | [payment_method_config_resource_payment_method_properties](payment-method-config-resource-payment-method-properties.md) | No |  |

