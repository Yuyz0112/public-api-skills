# digital-experience-monitoring_device

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `alwaysOn` | boolean | No |  |
| `batteryCharging` | boolean | No |  |
| `batteryCycles` | integer (int64) | No |  |
| `batteryPct` | number (float) | No |  |
| `colo` | [digital-experience-monitoring_colo](digital-experience-monitoring-colo.md) | Yes |  |
| `connectionType` | string | No |  |
| `cpuPct` | number (float) | No |  |
| `cpuPctByApp` | digital-experience-monitoring_cpu_pct_by_app[] | No |  |
| `deviceId` | string | Yes | Device identifier (UUID v4) |
| `deviceIpv4` | [digital-experience-monitoring_ip_info](digital-experience-monitoring-ip-info.md) | No |  |
| `deviceIpv6` | [digital-experience-monitoring_ip_info](digital-experience-monitoring-ip-info.md) | No |  |
| `deviceName` | string | No | Device identifier (human readable) |
| `diskReadBps` | integer (int64) | No |  |
| `diskUsagePct` | number (float) | No |  |
| `diskWriteBps` | integer (int64) | No |  |
| `dohSubdomain` | string | No |  |
| `estimatedLossPct` | number (float) | No |  |
| `firewallEnabled` | boolean | No |  |
| `gatewayIpv4` | [digital-experience-monitoring_ip_info](digital-experience-monitoring-ip-info.md) | No |  |
| `gatewayIpv6` | [digital-experience-monitoring_ip_info](digital-experience-monitoring-ip-info.md) | No |  |
| `handshakeLatencyMs` | number (int64) | No |  |
| `ispIpv4` | [digital-experience-monitoring_ip_info](digital-experience-monitoring-ip-info.md) | No |  |
| `ispIpv6` | [digital-experience-monitoring_ip_info](digital-experience-monitoring-ip-info.md) | No |  |
| `metal` | string | No |  |
| `mode` | [digital-experience-monitoring_mode](digital-experience-monitoring-mode.md) | Yes |  |
| `networkRcvdBps` | integer (int64) | No |  |
| `networkSentBps` | integer (int64) | No |  |
| `networkSsid` | string | No |  |
| `personEmail` | [digital-experience-monitoring_personEmail](digital-experience-monitoring-personEmail.md) | No |  |
| `platform` | [digital-experience-monitoring_platform](digital-experience-monitoring-platform.md) | Yes |  |
| `ramAvailableKb` | integer (int64) | No |  |
| `ramUsedPct` | number (float) | No |  |
| `ramUsedPctByApp` | digital-experience-monitoring_ram_used_pct_by_app[] | No |  |
| `status` | [digital-experience-monitoring_status](digital-experience-monitoring-status.md) | Yes |  |
| `switchLocked` | boolean | No |  |
| `timestamp` | [digital-experience-monitoring_timestamp](digital-experience-monitoring-timestamp.md) | Yes |  |
| `version` | [digital-experience-monitoring_version](digital-experience-monitoring-version.md) | Yes |  |
| `wifiStrengthDbm` | integer (int64) | No |  |

