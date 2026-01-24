# account

This is an object representing a Stripe account. You can retrieve it to see
properties on the account like its current requirements or if the account is
enabled to make live charges or receive payouts.

For accounts where [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection)
is `application`, which includes Custom accounts, the properties below are always
returned.

For accounts where [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection)
is `stripe`, which includes Standard and Express accounts, some properties are only returned
until you create an [Account Link](/api/account_links) or [Account Session](/api/account_sessions)
to start Connect Onboarding. Learn about the [differences between accounts](/connect/accounts).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `business_profile` | any | No | Business information about the account. |
| `business_type` | enum: company, government_entity, individual... | No | The business type. |
| `capabilities` | [account_capabilities](account-capabilities.md) | No |  |
| `charges_enabled` | boolean | No | Whether the account can process charges. |
| `company` | [legal_entity_company](legal-entity-company.md) | No |  |
| `controller` | [account_unification_account_controller](account-unification-account-controller.md) | No |  |
| `country` | string | No | The account's country. |
| `created` | integer (unix-time) | No | Time at which the account was connected. Measured in seconds since the Unix epoch. |
| `default_currency` | string | No | Three-letter ISO currency code representing the default currency for the account. This must be a currency that [Stripe supports in the account's country](https://stripe.com/docs/payouts). |
| `details_submitted` | boolean | No | Whether account details have been submitted. Accounts with Stripe Dashboard access, which includes Standard accounts, cannot receive payouts before this is true. Accounts where this is false should be directed to [an onboarding flow](/connect/onboarding) to finish submitting account details. |
| `email` | string | No | An email address associated with the account. It's not used for authentication and Stripe doesn't market to this field without explicit approval from the platform. |
| `external_accounts` | object | No | External accounts (bank accounts and debit cards) currently attached to this account. External accounts are only returned for requests where `controller[is_controller]` is true. |
| `future_requirements` | [account_future_requirements](account-future-requirements.md) | No |  |
| `groups` | any | No | The groups associated with the account. |
| `id` | string | Yes | Unique identifier for the object. |
| `individual` | [person](person.md) | No |  |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: account | Yes | String representing the object's type. Objects of the same type share the same value. |
| `payouts_enabled` | boolean | No | Whether the funds in this account can be paid out. |
| `requirements` | [account_requirements](account-requirements.md) | No |  |
| `settings` | any | No | Options for customizing how the account functions within Stripe. |
| `tos_acceptance` | [account_tos_acceptance](account-tos-acceptance.md) | No |  |
| `type` | enum: custom, express, none... | No | The Stripe account type. Can be `standard`, `express`, `custom`, or `none`. |

## Nested Fields

### `external_accounts`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | any[] | Yes | The list contains all external accounts that have been attached to the Stripe account. These may be bank accounts or cards. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |

