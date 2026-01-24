# issuing_card_apple_pay

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `eligible` | boolean | Yes | Apple Pay Eligibility |
| `ineligible_reason` | enum: missing_agreement, missing_cardholder_contact, unsupported_region | No | Reason the card is ineligible for Apple Pay |

