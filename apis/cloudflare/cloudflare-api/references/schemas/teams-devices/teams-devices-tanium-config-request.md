# teams-devices_tanium_config_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `access_client_id` | string | No | If present, this id will be passed in the `CF-Access-Client-ID` header when hitting the `api_url`. |
| `access_client_secret` | string | No | If present, this secret will be passed in the `CF-Access-Client-Secret` header when hitting the `api_url`. |
| `api_url` | string | Yes | The Tanium API URL. |
| `client_secret` | string | Yes | The Tanium client secret. |

