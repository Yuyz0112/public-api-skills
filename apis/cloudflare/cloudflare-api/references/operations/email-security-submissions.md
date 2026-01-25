# GET /accounts/{account_id}/email-security/submissions

**Resource:** [Email Security](../resources/Email-Security.md)
**Get reclassify submissions**
**Operation ID:** `email_security_submissions`

This endpoint returns information for submissions to made to reclassify emails.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `start` | query | string (date-time) | No | The beginning of the search date range.
Defaults to `now - 30 days`. |
| `end` | query | string (date-time) | No | The end of the search date range.
Defaults to `now`. |
| `type` | query | any | No |  |
| `submission_id` | query | string | No |  |
| `original_disposition` | query | any | No |  |
| `requested_disposition` | query | any | No |  |
| `outcome_disposition` | query | any | No |  |
| `status` | query | string | No |  |
| `query` | query | string | No |  |
| `page` | query | integer (int32) | No | The page number of paginated results. |
| `per_page` | query | integer (int32) | No | The number of results per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**
