# issuing_card_google_pay

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `eligible` | boolean | Yes | Google Pay Eligibility |
| `ineligible_reason` | enum: missing_agreement, missing_cardholder_contact, unsupported_region | No | Reason the card is ineligible for Google Pay |

