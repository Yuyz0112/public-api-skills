# terminal_configuration_configuration_resource_wifi_config

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enterprise_eap_peap` | [terminal_configuration_configuration_resource_enterprise_peap_wifi](terminal-configuration-configuration-resource-enterprise-peap-wifi.md) | No |  |
| `enterprise_eap_tls` | [terminal_configuration_configuration_resource_enterprise_tls_wifi](terminal-configuration-configuration-resource-enterprise-tls-wifi.md) | No |  |
| `personal_psk` | [terminal_configuration_configuration_resource_personal_psk_wifi](terminal-configuration-configuration-resource-personal-psk-wifi.md) | No |  |
| `type` | enum: enterprise_eap_peap, enterprise_eap_tls, personal_psk | Yes | Security type of the WiFi network. The hash with the corresponding name contains the credentials for this security type. |

