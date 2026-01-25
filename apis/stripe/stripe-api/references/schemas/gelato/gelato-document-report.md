# gelato_document_report

Result from a document check

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `address` | any | No | Address as it appears in the document. |
| `dob` | any | No | Date of birth as it appears in the document. |
| `error` | any | No | Details on the verification error. Present when status is `unverified`. |
| `expiration_date` | any | No | Expiration date of the document. |
| `files` | string[] | No | Array of [File](https://docs.stripe.com/api/files) ids containing images for this document. |
| `first_name` | string | No | First name as it appears in the document. |
| `issued_date` | any | No | Issued date of the document. |
| `issuing_country` | string | No | Issuing country of the document. |
| `last_name` | string | No | Last name as it appears in the document. |
| `number` | string | No | Document ID number. |
| `sex` | enum: [redacted], female, male... | No | Sex of the person in the document. |
| `status` | enum: unverified, verified | Yes | Status of this `document` check. |
| `type` | enum: driving_license, id_card, passport | No | Type of the document. |
| `unparsed_place_of_birth` | string | No | Place of birth as it appears in the document. |
| `unparsed_sex` | string | No | Sex as it appears in the document. |

