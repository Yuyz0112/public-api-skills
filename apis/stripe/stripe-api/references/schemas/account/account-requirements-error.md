# account_requirements_error

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | enum: external_request, information_missing, invalid_address_city_state_postal_code... | Yes | The code for the type of error. |
| `reason` | string | Yes | An informative message that indicates the error type and provides additional details about the error. |
| `requirement` | string | Yes | The specific user onboarding requirement field (in the requirements hash) that needs to be resolved. |

