# identity.verification_report

A VerificationReport is the result of an attempt to collect and verify data from a user.
The collection of verification checks performed is determined from the `type` and `options`
parameters used. You can find the result of each verification check performed in the
appropriate sub-resource: `document`, `id_number`, `selfie`.

Each VerificationReport contains a copy of any data collected by the user as well as
reference IDs which can be used to access collected images through the [FileUpload](https://docs.stripe.com/api/files)
API. To configure and create VerificationReports, use the
[VerificationSession](https://docs.stripe.com/api/identity/verification_sessions) API.

Related guide: [Accessing verification results](https://docs.stripe.com/identity/verification-sessions#results).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `client_reference_id` | string | No | A string to reference this user. This can be a customer ID, a session ID, or similar, and can be used to reconcile this verification with your internal systems. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `document` | [gelato_document_report](gelato-document-report.md) | No |  |
| `email` | [gelato_email_report](gelato-email-report.md) | No |  |
| `id` | string | Yes | Unique identifier for the object. |
| `id_number` | [gelato_id_number_report](gelato-id-number-report.md) | No |  |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: identity.verification_report | Yes | String representing the object's type. Objects of the same type share the same value. |
| `options` | [gelato_verification_report_options](gelato-verification-report-options.md) | No |  |
| `phone` | [gelato_phone_report](gelato-phone-report.md) | No |  |
| `selfie` | [gelato_selfie_report](gelato-selfie-report.md) | No |  |
| `type` | enum: document, id_number, verification_flow | Yes | Type of report. |
| `verification_flow` | string | No | The configuration token of a verification flow from the dashboard. |
| `verification_session` | string | No | ID of the VerificationSession that created this report. |

