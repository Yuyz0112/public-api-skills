# person

This is an object representing a person associated with a Stripe account.

A platform can only access a subset of data in a person for an account where [account.controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `stripe`, which includes Standard and Express accounts, after creating an Account Link or Account Session to start Connect onboarding.

See the [Standard onboarding](/connect/standard-accounts) or [Express onboarding](/connect/express-accounts) documentation for information about prefilling information and account onboarding steps. Learn more about [handling identity verification with the API](/connect/handling-api-verification#person-information).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | string | Yes | The account the person is associated with. |
| `additional_tos_acceptances` | [person_additional_tos_acceptances](person-additional-tos-acceptances.md) | No |  |
| `address` | [address](address.md) | No |  |
| `address_kana` | any | No |  |
| `address_kanji` | any | No |  |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `dob` | [legal_entity_dob](legal-entity-dob.md) | No |  |
| `email` | string | No | The person's email address. Also available for accounts where [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `stripe`. |
| `first_name` | string | No | The person's first name. Also available for accounts where [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `stripe`. |
| `first_name_kana` | string | No | The Kana variation of the person's first name (Japan only). Also available for accounts where [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `stripe`. |
| `first_name_kanji` | string | No | The Kanji variation of the person's first name (Japan only). Also available for accounts where [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `stripe`. |
| `full_name_aliases` | string[] | No | A list of alternate names or aliases that the person is known by. Also available for accounts where [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `stripe`. |
| `future_requirements` | any | No |  |
| `gender` | string | No | The person's gender. |
| `id` | string | Yes | Unique identifier for the object. |
| `id_number_provided` | boolean | No | Whether the person's `id_number` was provided. True if either the full ID number was provided or if only the required part of the ID number was provided (ex. last four of an individual's SSN for the US indicated by `ssn_last_4_provided`). |
| `id_number_secondary_provided` | boolean | No | Whether the person's `id_number_secondary` was provided. |
| `last_name` | string | No | The person's last name. Also available for accounts where [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `stripe`. |
| `last_name_kana` | string | No | The Kana variation of the person's last name (Japan only). Also available for accounts where [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `stripe`. |
| `last_name_kanji` | string | No | The Kanji variation of the person's last name (Japan only). Also available for accounts where [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `stripe`. |
| `maiden_name` | string | No | The person's maiden name. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `nationality` | string | No | The country where the person is a national. |
| `object` | enum: person | Yes | String representing the object's type. Objects of the same type share the same value. |
| `phone` | string | No | The person's phone number. |
| `political_exposure` | enum: existing, none | No | Indicates if the person or any of their representatives, family members, or other closely related persons, declares that they hold or have held an important public job or function, in any jurisdiction. |
| `registered_address` | [address](address.md) | No |  |
| `relationship` | [person_relationship](person-relationship.md) | No |  |
| `requirements` | any | No |  |
| `ssn_last_4_provided` | boolean | No | Whether the last four digits of the person's Social Security number have been provided (U.S. only). |
| `us_cfpb_data` | any | No | Demographic data related to the person. |
| `verification` | [legal_entity_person_verification](legal-entity-person-verification.md) | No |  |

