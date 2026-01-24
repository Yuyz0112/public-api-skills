# country_spec

Stripe needs to collect certain pieces of information about each account
created. These requirements can differ depending on the account's country. The
Country Specs API makes these rules available to your integration.

You can also view the information from this API call as [an online
guide](/docs/connect/required-verification-information).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `default_currency` | string | Yes | The default currency for this country. This applies to both payment methods and bank accounts. |
| `id` | string | Yes | Unique identifier for the object. Represented as the ISO country code for this country. |
| `object` | enum: country_spec | Yes | String representing the object's type. Objects of the same type share the same value. |
| `supported_bank_account_currencies` | object | Yes | Currencies that can be accepted in the specific country (for transfers). |
| `supported_payment_currencies` | string[] | Yes | Currencies that can be accepted in the specified country (for payments). |
| `supported_payment_methods` | string[] | Yes | Payment methods available in the specified country. You may need to enable some payment methods (e.g., [ACH](https://stripe.com/docs/ach)) on your account before they appear in this list. The `stripe` payment method refers to [charging through your platform](https://stripe.com/docs/connect/destination-charges). |
| `supported_transfer_countries` | string[] | Yes | Countries that can accept transfers from the specified country. |
| `verification_fields` | [country_spec_verification_fields](country-spec-verification-fields.md) | Yes |  |

