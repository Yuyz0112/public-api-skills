# zones_automatic_platform_optimization

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cache_by_device_type` | boolean | Yes | Indicates whether or not [cache by device type](https://developers.cloudflare.com/automatic-platform-optimization/reference/cache-device-type/) is enabled. |
| `cf` | boolean | Yes | Indicates whether or not Cloudflare proxy is enabled. |
| `enabled` | boolean | Yes | Indicates whether or not Automatic Platform Optimization is enabled. |
| `hostnames` | string[] | Yes | An array of hostnames where Automatic Platform Optimization for WordPress is activated. |
| `wordpress` | boolean | Yes | Indicates whether or not site is powered by WordPress. |
| `wp_plugin` | boolean | Yes | Indicates whether or not [Cloudflare for WordPress plugin](https://wordpress.org/plugins/cloudflare/) is installed. |

