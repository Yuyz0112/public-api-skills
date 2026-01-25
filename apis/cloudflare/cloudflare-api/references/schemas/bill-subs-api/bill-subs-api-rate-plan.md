# bill-subs-api_rate_plan

The rate plan applied to the subscription.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `currency` | string | No | The currency applied to the rate plan subscription. |
| `externally_managed` | boolean | No | Whether this rate plan is managed externally from Cloudflare. |
| `id` | string | No | The ID of the rate plan. |
| `is_contract` | boolean | No | Whether a rate plan is enterprise-based (or newly adopted term contract). |
| `public_name` | string | No | The full name of the rate plan. |
| `scope` | string | No | The scope that this rate plan applies to. |
| `sets` | string[] | No | The list of sets this rate plan applies to. Returns array of strings. |

