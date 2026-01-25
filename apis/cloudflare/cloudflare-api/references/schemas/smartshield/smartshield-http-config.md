# smartshield_http_config

Parameters specific to an HTTP or HTTPS health check.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allow_insecure` | boolean | No | Do not validate the certificate when the health check uses HTTPS. |
| `expected_body` | string | No | A case-insensitive sub-string to look for in the response body. If this string is not found, the origin will be marked as unhealthy. |
| `expected_codes` | string[] | No | The expected HTTP response codes (e.g. "200") or code ranges (e.g. "2xx" for all codes starting with 2) of the health check. |
| `follow_redirects` | boolean | No | Follow redirects if the origin returns a 3xx status code. |
| `header` | object | No | The HTTP request headers to send in the health check. It is recommended you set a Host header by default. The User-Agent header cannot be overridden. |
| `method` | enum: GET, HEAD | No | The HTTP method to use for the health check. |
| `path` | string | No | The endpoint path to health check against. |
| `port` | integer | No | Port number to connect to for the health check. Defaults to 80 if type is HTTP or 443 if type is HTTPS. |

