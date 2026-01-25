# lists_item_hostname

Valid characters for hostnames are ASCII(7) letters from a to z, the digits from 0 to 9, wildcards (*), and the hyphen (-).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `exclude_exact_hostname` | boolean | No | Only applies to wildcard hostnames (e.g., *.example.com). When true (default), only subdomains are blocked. When false, both the root domain and subdomains are blocked. |
| `url_hostname` | string | Yes |  |

