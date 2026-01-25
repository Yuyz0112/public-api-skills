# GET /accounts/{account_id}/email-security/investigate

**Resource:** [Email Security](../resources/Email-Security.md)
**Search email messages**
**Operation ID:** `email_security_investigate`

Returns information for each email that matches the search parameter(s).
If the search takes too long, the endpoint returns 202 with a Location header
pointing to a polling endpoint where results can be retrieved once ready.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `start` | query | string (date-time) | No | The beginning of the search date range.
Defaults to `now - 30 days`. |
| `end` | query | string (date-time) | No | The end of the search date range.
Defaults to `now`. |
| `query` | query | string | No | The space-delimited term used in the query. The search is case-insensitive.

The content of the following email metadata fields are searched:
* alert_id
* CC
* From (envelope_from)
* From Name
* final_disposition
* md5 hash (of any attachment)
* sha1 hash (of any attachment)
* sha256 hash (of any attachment)
* name (of any attachment)
* Reason
* Received DateTime (yyyy-mm-ddThh:mm:ss)
* Sent DateTime (yyyy-mm-ddThh:mm:ss)
* ReplyTo
* To (envelope_to)
* To Name
* Message-ID
* smtp_helo_server_ip
* smtp_previous_hop_ip
* x_originating_ip
* Subject |
| `detections_only` | query | boolean | No | Determines if the search results will include detections or not. |
| `action_log` | query | boolean | No | Determines if the message action log is included in the response. |
| `final_disposition` | query | any | No | The dispositions the search filters by. |
| `metric` | query | string | No |  |
| `message_action` | query | any | No | The message actions the search filters by. |
| `recipient` | query | string | No |  |
| `sender` | query | string | No |  |
| `alert_id` | query | string | No |  |
| `domain` | query | string | No | The sender domains the search filters by. |
| `message_id` | query | string | No |  |
| `subject` | query | string | No |  |
| `cursor` | query | string | No |  |
| `per_page` | query | integer (int32) | No | The number of results per page. |
| `page` | query | integer (int32) | No | Deprecated: Use cursor pagination instead. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Contains the search results for the provided query. |
| 202 | The search is taking longer than expected. Use the Location header to poll for results. |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**
