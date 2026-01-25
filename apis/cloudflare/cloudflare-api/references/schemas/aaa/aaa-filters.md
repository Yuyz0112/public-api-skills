# aaa_filters

Optional filters that allow you to be alerted only on a subset of events for that alert type based on some criteria. This is only available for select alert types. See alert type documentation for more details.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actions` | string[] | No | Usage depends on specific alert type |
| `affected_asns` | string[] | No | Used for configuring radar_notification |
| `affected_components` | string[] | No | Used for configuring incident_alert |
| `affected_locations` | string[] | No | Used for configuring radar_notification |
| `airport_code` | string[] | No | Used for configuring maintenance_event_notification |
| `alert_trigger_preferences` | string[] | No | Usage depends on specific alert type |
| `alert_trigger_preferences_value` | string[] | No | Usage depends on specific alert type |
| `enabled` | string[] | No | Used for configuring load_balancing_pool_enablement_alert |
| `environment` | string[] | No | Used for configuring pages_event_alert |
| `event` | string[] | No | Used for configuring pages_event_alert |
| `event_source` | string[] | No | Used for configuring load_balancing_health_alert |
| `event_type` | string[] | No | Usage depends on specific alert type |
| `group_by` | string[] | No | Usage depends on specific alert type |
| `health_check_id` | string[] | No | Used for configuring health_check_status_notification |
| `incident_impact` | string[] | No | Used for configuring incident_alert |
| `input_id` | string[] | No | Used for configuring stream_live_notifications |
| `insight_class` | string[] | No | Used for configuring security_insights_alert |
| `limit` | string[] | No | Used for configuring billing_usage_alert |
| `logo_tag` | string[] | No | Used for configuring logo_match_alert |
| `megabits_per_second` | string[] | No | Used for configuring advanced_ddos_attack_l4_alert |
| `new_health` | string[] | No | Used for configuring load_balancing_health_alert |
| `new_status` | string[] | No | Used for configuring tunnel_health_event |
| `packets_per_second` | string[] | No | Used for configuring advanced_ddos_attack_l4_alert |
| `pool_id` | string[] | No | Usage depends on specific alert type |
| `pop_names` | string[] | No | Usage depends on specific alert type |
| `product` | string[] | No | Used for configuring billing_usage_alert |
| `project_id` | string[] | No | Used for configuring pages_event_alert |
| `protocol` | string[] | No | Used for configuring advanced_ddos_attack_l4_alert |
| `query_tag` | string[] | No | Usage depends on specific alert type |
| `requests_per_second` | string[] | No | Used for configuring advanced_ddos_attack_l7_alert |
| `selectors` | string[] | No | Usage depends on specific alert type |
| `services` | string[] | No | Used for configuring clickhouse_alert_fw_ent_anomaly |
| `slo` | string[] | No | Usage depends on specific alert type |
| `status` | string[] | No | Used for configuring health_check_status_notification |
| `target_hostname` | string[] | No | Used for configuring advanced_ddos_attack_l7_alert |
| `target_ip` | string[] | No | Used for configuring advanced_ddos_attack_l4_alert |
| `target_zone_name` | string[] | No | Used for configuring advanced_ddos_attack_l7_alert |
| `traffic_exclusions` | string[] | No | Used for configuring traffic_anomalies_alert |
| `tunnel_id` | string[] | No | Used for configuring tunnel_health_event |
| `tunnel_name` | string[] | No | Usage depends on specific alert type |
| `type` | string[] | No | Usage depends on specific alert type |
| `where` | string[] | No | Usage depends on specific alert type |
| `zones` | string[] | No | Usage depends on specific alert type |

