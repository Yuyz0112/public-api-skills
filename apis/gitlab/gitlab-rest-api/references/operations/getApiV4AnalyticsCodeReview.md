# GET /api/v4/analytics/code_review

**Resource:** [Code review analytics](../resources/Code-review-analytics.md)
**List code review information about project**
**Operation ID:** `getApiV4AnalyticsCodeReview`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `project_id` | query | integer | Yes | Project ID |
| `label_name` | query | any | No | Array of label names to filter by |
| `milestone_title` | query | string | No | Milestone title to filter by |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `not` | query | object | No | Filters by the specified parameters |
| `not[label_name]` | query | any | No | Array of label names to filter by |
| `not[milestone_title]` | query | string | No | Milestone title to filter by |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesAnalyticsCodeReviewMergeRequest](../schemas/APIEntitiesAnalyticsCodeReviewMergeRequest/APIEntitiesAnalyticsCodeReviewMergeRequest.md)

