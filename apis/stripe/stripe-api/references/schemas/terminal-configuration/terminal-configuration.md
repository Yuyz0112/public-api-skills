# terminal.configuration

A Configurations object represents how features should be configured for terminal readers.
For information about how to use it, see the [Terminal configurations documentation](https://docs.stripe.com/terminal/fleet/configurations-overview).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bbpos_wisepad3` | [terminal_configuration_configuration_resource_device_type_specific_config](terminal-configuration-configuration-resource-device-type-specific-config.md) | No |  |
| `bbpos_wisepos_e` | [terminal_configuration_configuration_resource_device_type_specific_config](terminal-configuration-configuration-resource-device-type-specific-config.md) | No |  |
| `id` | string | Yes | Unique identifier for the object. |
| `is_account_default` | boolean | No | Whether this Configuration is the default for your account |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `name` | string | No | String indicating the name of the Configuration object, set by the user |
| `object` | enum: terminal.configuration | Yes | String representing the object's type. Objects of the same type share the same value. |
| `offline` | [terminal_configuration_configuration_resource_offline_config](terminal-configuration-configuration-resource-offline-config.md) | No |  |
| `reboot_window` | [terminal_configuration_configuration_resource_reboot_window](terminal-configuration-configuration-resource-reboot-window.md) | No |  |
| `stripe_s700` | [terminal_configuration_configuration_resource_device_type_specific_config](terminal-configuration-configuration-resource-device-type-specific-config.md) | No |  |
| `tipping` | [terminal_configuration_configuration_resource_tipping](terminal-configuration-configuration-resource-tipping.md) | No |  |
| `verifone_p400` | [terminal_configuration_configuration_resource_device_type_specific_config](terminal-configuration-configuration-resource-device-type-specific-config.md) | No |  |
| `wifi` | [terminal_configuration_configuration_resource_wifi_config](terminal-configuration-configuration-resource-wifi-config.md) | No |  |

