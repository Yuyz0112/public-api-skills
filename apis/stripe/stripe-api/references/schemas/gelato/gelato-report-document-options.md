# gelato_report_document_options

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allowed_types` | string[] | No | Array of strings of allowed identity document types. If the provided identity document isn’t one of the allowed types, the verification check will fail with a document_type_not_allowed error code. |
| `require_id_number` | boolean | No | Collect an ID number and perform an [ID number check](https://docs.stripe.com/identity/verification-checks?type=id-number) with the document’s extracted name and date of birth. |
| `require_live_capture` | boolean | No | Disable image uploads, identity document images have to be captured using the device’s camera. |
| `require_matching_selfie` | boolean | No | Capture a face image and perform a [selfie check](https://docs.stripe.com/identity/verification-checks?type=selfie) comparing a photo ID and a picture of your user’s face. [Learn more](https://docs.stripe.com/identity/selfie). |

