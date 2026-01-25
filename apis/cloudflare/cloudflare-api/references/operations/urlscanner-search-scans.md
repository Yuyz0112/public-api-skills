# GET /accounts/{account_id}/urlscanner/scan

**Resource:** [URL Scanner (Deprecated)](../resources/URL-Scanner-Deprecated.md)
**Search URL scans**
**Operation ID:** `urlscanner-search-scans`
⚠️ **Deprecated**

Search scans by date and webpages' requests, including full URL (after redirects), hostname, and path. <br/> A successful scan will appear in search results a few minutes after finishing but may take much longer if the system in under load. By default, only successfully completed scans will appear in search results, unless searching by `scanId`. Please take into account that older scans may be removed from the search index at an unspecified time.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `scan_id` | query | string (uuid) | No | Scan UUID. |
| `limit` | query | integer | No | Limit the number of objects in the response. |
| `next_cursor` | query | string | No | Pagination cursor to get the next set of results. |
| `date_start` | query | string (date-time) | No | Filter scans requested after date (inclusive). |
| `date_end` | query | string (date-time) | No | Filter scans requested before date (inclusive). |
| `url` | query | string | No | Filter scans by URL of _any_ request made by the webpage |
| `hostname` | query | string | No | Filter scans by hostname of _any_ request made by the webpage. |
| `path` | query | string | No | Filter scans by url path of _any_ request made by the webpage. |
| `ip` | query | string | No | Filter scans by IP address (IPv4 or IPv6) of _any_ request made by the webpage. |
| `hash` | query | string | No | Filter scans by hash of any html/js/css request made by the webpage. |
| `page_url` | query | string | No | Filter scans by submitted or scanned URL |
| `page_hostname` | query | string | No | Filter scans by main page hostname (domain of effective URL). |
| `page_path` | query | string | No | Filter scans by exact match of effective URL path (also supports suffix search). |
| `page_asn` | query | string | No | Filter scans by main page Autonomous System Number (ASN). |
| `page_ip` | query | string | No | Filter scans by  main page IP address (IPv4 or IPv6). |
| `account_scans` | query | boolean | No | Return only scans created by account. |
| `is_malicious` | query | boolean | No | Filter scans by malicious verdict. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Search results |
| 400 | Invalid params. |

## Security

- **api_token**
- **api_email**
- **api_key**
