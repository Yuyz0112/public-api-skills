# cancellation_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `comment` | string | No | Additional comments about why the user canceled the subscription, if the subscription was canceled explicitly by the user. |
| `feedback` | enum: customer_service, low_quality, missing_features... | No | The customer submitted reason for why they canceled, if the subscription was canceled explicitly by the user. |
| `reason` | enum: cancellation_requested, payment_disputed, payment_failed | No | Why this subscription was canceled. |

