# rulesets_RuleRatelimit

An object configuring the rule's rate limit behavior.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `characteristics` | string[] | Yes | Characteristics of the request on which the rate limit counter will be incremented. |
| `counting_expression` | string | No | An expression that defines when the rate limit counter should be incremented. It defaults to the same as the rule's expression. |
| `mitigation_timeout` | integer | No | Period of time in seconds after which the action will be disabled following its first execution. |
| `period` | integer | Yes | Period in seconds over which the counter is being incremented. |
| `requests_per_period` | integer | No | The threshold of requests per period after which the action will be executed for the first time. |
| `requests_to_origin` | boolean | No | Whether counting is only performed when an origin is reached. |
| `score_per_period` | integer | No | The score threshold per period for which the action will be executed the first time. |
| `score_response_header_name` | string | No | A response header name provided by the origin, which contains the score to increment rate limit counter with. |

