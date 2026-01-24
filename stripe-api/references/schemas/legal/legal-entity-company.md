# legal_entity_company

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `address` | [address](address.md) | No |  |
| `address_kana` | any | No | The Kana variation of the company's primary address (Japan only). |
| `address_kanji` | any | No | The Kanji variation of the company's primary address (Japan only). |
| `directors_provided` | boolean | No | Whether the company's directors have been provided. This Boolean will be `true` if you've manually indicated that all directors are provided via [the `directors_provided` parameter](https://docs.stripe.com/api/accounts/update#update_account-company-directors_provided). |
| `directorship_declaration` | any | No | This hash is used to attest that the director information provided to Stripe is both current and correct. |
| `executives_provided` | boolean | No | Whether the company's executives have been provided. This Boolean will be `true` if you've manually indicated that all executives are provided via [the `executives_provided` parameter](https://docs.stripe.com/api/accounts/update#update_account-company-executives_provided), or if Stripe determined that sufficient executives were provided. |
| `export_license_id` | string | No | The export license ID number of the company, also referred as Import Export Code (India only). |
| `export_purpose_code` | string | No | The purpose code to use for export transactions (India only). |
| `name` | string | No | The company's legal name. Also available for accounts where [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `stripe`. |
| `name_kana` | string | No | The Kana variation of the company's legal name (Japan only). Also available for accounts where [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `stripe`. |
| `name_kanji` | string | No | The Kanji variation of the company's legal name (Japan only). Also available for accounts where [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `stripe`. |
| `owners_provided` | boolean | No | Whether the company's owners have been provided. This Boolean will be `true` if you've manually indicated that all owners are provided via [the `owners_provided` parameter](https://docs.stripe.com/api/accounts/update#update_account-company-owners_provided), or if Stripe determined that sufficient owners were provided. Stripe determines ownership requirements using both the number of owners provided and their total percent ownership (calculated by adding the `percent_ownership` of each owner together). |
| `ownership_declaration` | any | No | This hash is used to attest that the beneficial owner information provided to Stripe is both current and correct. |
| `ownership_exemption_reason` | enum: qualified_entity_exceeds_ownership_threshold, qualifies_as_financial_institution | No | This value is used to determine if a business is exempt from providing ultimate beneficial owners. See [this support article](https://support.stripe.com/questions/exemption-from-providing-ownership-details) and [changelog](https://docs.stripe.com/changelog/acacia/2025-01-27/ownership-exemption-reason-accounts-api) for more details. |
| `phone` | string | No | The company's phone number (used for verification). |
| `registration_date` | [legal_entity_registration_date](legal-entity-registration-date.md) | No |  |
| `representative_declaration` | any | No | This hash is used to attest that the representative is authorized to act as the representative of their legal entity. |
| `structure` | enum: free_zone_establishment, free_zone_llc, government_instrumentality... | No | The category identifying the legal structure of the company or legal entity. Also available for accounts where [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `stripe`. See [Business structure](https://docs.stripe.com/connect/identity-verification#business-structure) for more details. |
| `tax_id_provided` | boolean | No | Whether the company's business ID number was provided. |
| `tax_id_registrar` | string | No | The jurisdiction in which the `tax_id` is registered (Germany-based companies only). |
| `vat_id_provided` | boolean | No | Whether the company's business VAT number was provided. |
| `verification` | any | No | Information on the verification state of the company. |

