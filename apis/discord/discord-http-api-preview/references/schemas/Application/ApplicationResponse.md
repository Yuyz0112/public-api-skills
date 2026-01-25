# ApplicationResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `name` | string | Yes |  |
| `icon` | string,null | No |  |
| `description` | string | Yes |  |
| `type` | any | No |  |
| `cover_image` | string | No |  |
| `primary_sku_id` | [SnowflakeType](SnowflakeType.md) | No |  |
| `bot` | [UserResponse](UserResponse.md) | No |  |
| `slug` | string | No |  |
| `guild_id` | [SnowflakeType](SnowflakeType.md) | No |  |
| `rpc_origins` | string,null[] | No |  |
| `bot_public` | boolean | No |  |
| `bot_require_code_grant` | boolean | No |  |
| `terms_of_service_url` | string (uri) | No |  |
| `privacy_policy_url` | string (uri) | No |  |
| `custom_install_url` | string (uri) | No |  |
| `install_params` | [ApplicationOAuth2InstallParamsResponse](ApplicationOAuth2InstallParamsResponse.md) | No |  |
| `integration_types_config` | object | No |  |
| `verify_key` | string | Yes |  |
| `flags` | integer (int32) | Yes |  |
| `max_participants` | integer,null (int32) | No |  |
| `tags` | string[] | No |  |

