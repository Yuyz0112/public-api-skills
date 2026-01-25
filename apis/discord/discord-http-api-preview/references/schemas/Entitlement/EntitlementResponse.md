# EntitlementResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `sku_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `application_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `user_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `guild_id` | any | No |  |
| `deleted` | boolean | Yes |  |
| `starts_at` | string,null (date-time) | No |  |
| `ends_at` | string,null (date-time) | No |  |
| `type` | [EntitlementTypes](EntitlementTypes.md) | Yes |  |
| `fulfilled_at` | string,null (date-time) | No |  |
| `fulfillment_status` | any | No |  |
| `consumed` | boolean,null | No |  |
| `gifter_user_id` | any | No |  |
| `parent_id` | any | No |  |

