# GET /accounts/{account_id}/urlscanner/v2/search

**Resource:** [URL Scanner](../resources/URL-Scanner.md)
**Search URL scans**
**Operation ID:** `urlscanner-search-scans-v2`

Use a subset of ElasticSearch Query syntax to filter scans. Some example queries:<br/> <br/>- 'path:"/bundles/jquery.js"': Searches for scans who requested resources with the given path.<br/>- 'page.asn:AS24940 AND hash:xxx': Websites hosted in AS24940 where a resource with the given hash was downloaded.<br/>- 'page.domain:microsoft* AND verdicts.malicious:true AND NOT page.domain:microsoft.com': malicious scans whose hostname starts with "microsoft".<br/>- 'apikey:me AND date:[2025-01 TO 2025-02]': my scans from 2025 January to 2025 February.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `size` | query | integer | No | Limit the number of objects in the response. |
| `q` | query | string | No | Filter scans |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Search results |
| 400 | Invalid input. |

## Security

- **api_token**
- **api_email**
- **api_key**
