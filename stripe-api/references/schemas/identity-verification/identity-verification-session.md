# identity.verification_session

A VerificationSession guides you through the process of collecting and verifying the identities
of your users. It contains details about the type of verification, such as what [verification
check](/docs/identity/verification-checks) to perform. Only create one VerificationSession for
each verification in your system.

A VerificationSession transitions through [multiple
statuses](/docs/identity/how-sessions-work) throughout its lifetime as it progresses through
the verification flow. The VerificationSession contains the user's verified data after
verification checks are complete.

Related guide: [The Verification Sessions API](https://docs.stripe.com/identity/verification-sessions)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `client_reference_id` | string | No | A string to reference this user. This can be a customer ID, a session ID, or similar, and can be used to reconcile this verification with your internal systems. |
| `client_secret` | string | No | The short-lived client secret used by Stripe.js to [show a verification modal](https://docs.stripe.com/js/identity/modal) inside your app. This client secret expires after 24 hours and can only be used once. Don’t store it, log it, embed it in a URL, or expose it to anyone other than the user. Make sure that you have TLS enabled on any page that includes the client secret. Refer to our docs on [passing the client secret to the frontend](https://docs.stripe.com/identity/verification-sessions#client-secret) to learn more. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `id` | string | Yes | Unique identifier for the object. |
| `last_error` | any | No | If present, this property tells you the last error encountered when processing the verification. |
| `last_verification_report` | any | No | ID of the most recent VerificationReport. [Learn more about accessing detailed verification results.](https://docs.stripe.com/identity/verification-sessions#results) |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: identity.verification_session | Yes | String representing the object's type. Objects of the same type share the same value. |
| `options` | any | No | A set of options for the session’s verification checks. |
| `provided_details` | any | No | Details provided about the user being verified. These details may be shown to the user. |
| `redaction` | any | No | Redaction status of this VerificationSession. If the VerificationSession is not redacted, this field will be null. |
| `related_customer` | string | No | Customer ID |
| `related_customer_account` | string | No | The ID of the Account representing a customer. |
| `related_person` | [gelato_related_person](gelato-related-person.md) | No |  |
| `status` | enum: canceled, processing, requires_input... | Yes | Status of this VerificationSession. [Learn more about the lifecycle of sessions](https://docs.stripe.com/identity/how-sessions-work). |
| `type` | enum: document, id_number, verification_flow | Yes | The type of [verification check](https://docs.stripe.com/identity/verification-checks) to be performed. |
| `url` | string | No | The short-lived URL that you use to redirect a user to Stripe to submit their identity information. This URL expires after 48 hours and can only be used once. Don’t store it, log it, send it in emails or expose it to anyone other than the user. Refer to our docs on [verifying identity documents](https://docs.stripe.com/identity/verify-identity-documents?platform=web&type=redirect) to learn how to redirect users to Stripe. |
| `verification_flow` | string | No | The configuration token of a verification flow from the dashboard. |
| `verified_outputs` | any | No | The user’s verified data. |

