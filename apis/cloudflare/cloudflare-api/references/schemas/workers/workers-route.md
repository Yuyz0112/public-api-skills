# workers_route

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | any | Yes |  |
| `pattern` | string | Yes | Pattern to match incoming requests against. [Learn more](https://developers.cloudflare.com/workers/configuration/routing/routes/#matching-behavior). |
| `script` | string | No | Name of the script to run if the route matches. |

