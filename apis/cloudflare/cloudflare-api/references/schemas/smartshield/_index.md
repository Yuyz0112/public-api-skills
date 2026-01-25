# smartshield Schemas

40 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [smartshield_address](smartshield-address.md) | primitive | The hostname or IP address of the origin server to |
| [smartshield_api-response-collection](smartshield-api-response-collection.md) | allOf |  |
| [smartshield_api-response-common](smartshield-api-response-common.md) | object |  |
| [smartshield_api-response-common-failure](smartshield-api-response-common-failure.md) | object |  |
| [smartshield_api-response-single](smartshield-api-response-single.md) | allOf |  |
| [smartshield_base](smartshield-base.md) | object |  |
| [smartshield_cache_reserve_clear](smartshield-cache-reserve-clear.md) | allOf | You can use Cache Reserve Clear to clear your Cach |
| [smartshield_cache_reserve_clear_end_ts](smartshield-cache-reserve-clear-end-ts.md) | primitive | The time that the latest Cache Reserve Clear opera |
| [smartshield_cache_reserve_clear_response_value](smartshield-cache-reserve-clear-response-value.md) | object |  |
| [smartshield_cache_reserve_clear_start_ts](smartshield-cache-reserve-clear-start-ts.md) | primitive | The time that the latest Cache Reserve Clear opera |
| [smartshield_cache_reserve_clear_state](smartshield-cache-reserve-clear-state.md) | enum | The current state of the Cache Reserve Clear opera |
| [smartshield_check_regions](smartshield-check-regions.md) | array | A list of regions from which to run health checks. |
| [smartshield_consecutive_fails](smartshield-consecutive-fails.md) | primitive | The number of consecutive fails required from a he |
| [smartshield_consecutive_successes](smartshield-consecutive-successes.md) | primitive | The number of consecutive successes required from  |
| [smartshield_description](smartshield-description.md) | primitive | A human-readable description of the health check. |
| [smartshield_failure_reason](smartshield-failure-reason.md) | primitive | The current failure reason if status is unhealthy. |
| [smartshield_healthchecks](smartshield-healthchecks.md) | object |  |
| [smartshield_http_config](smartshield-http-config.md) | object | Parameters specific to an HTTP or HTTPS health che |
| [smartshield_identifier](smartshield-identifier.md) | primitive | Identifier. |
| [smartshield_interval](smartshield-interval.md) | primitive | The interval between each health check. Shorter in |
| [smartshield_messages](smartshield-messages.md) | array |  |
| [smartshield_name](smartshield-name.md) | primitive | A short name to identify the health check. Only al |
| [smartshield_query_healthcheck](smartshield-query-healthcheck.md) | object |  |
| [smartshield_response_collection](smartshield-response-collection.md) | allOf |  |
| [smartshield_result_info](smartshield-result-info.md) | object |  |
| [smartshield_retries](smartshield-retries.md) | primitive | The number of retries to attempt in case of a time |
| [smartshield_single_hc_id_response](smartshield-single-hc-id-response.md) | allOf |  |
| [smartshield_single_hc_response](smartshield-single-hc-response.md) | allOf |  |
| [smartshield_single_smart_shield_get_response](smartshield-single-smart-shield-get-response.md) | allOf |  |
| [smartshield_single_smart_shield_patch_response](smartshield-single-smart-shield-patch-response.md) | allOf |  |
| [smartshield_smart_shield_settings](smartshield-smart-shield-settings.md) | object | A consolidated object containing settings from mul |
| [smartshield_smart_shield_settings_get_response](smartshield-smart-shield-settings-get-response.md) | allOf | The full Smart Shield response from the GET and PA |
| [smartshield_smart_shield_settings_patch_body](smartshield-smart-shield-settings-patch-body.md) | object | The patch body for Smart Shield. |
| [smartshield_smart_shield_settings_patch_response](smartshield-smart-shield-settings-patch-response.md) | object | A consolidated object containing settings from mul |
| [smartshield_status](smartshield-status.md) | enum | The current status of the origin server according  |
| [smartshield_suspended](smartshield-suspended.md) | primitive | If suspended, no health checks are sent to the ori |
| [smartshield_tcp_config](smartshield-tcp-config.md) | object | Parameters specific to TCP health check. |
| [smartshield_timeout](smartshield-timeout.md) | primitive | The timeout (in seconds) before marking the health |
| [smartshield_timestamp](smartshield-timestamp.md) | primitive |  |
| [smartshield_type](smartshield-type.md) | primitive | The protocol to use for the health check. Currentl |
