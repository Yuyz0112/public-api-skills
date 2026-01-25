# digital-experience-monitoring Schemas

68 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [digital-experience-monitoring_account_identifier](digital-experience-monitoring-account-identifier.md) | primitive |  |
| [digital-experience-monitoring_aggregate_stat](digital-experience-monitoring-aggregate-stat.md) | object |  |
| [digital-experience-monitoring_aggregate_time_period](digital-experience-monitoring-aggregate-time-period.md) | object |  |
| [digital-experience-monitoring_aggregate_time_slot](digital-experience-monitoring-aggregate-time-slot.md) | object |  |
| [digital-experience-monitoring_api-response-collection](digital-experience-monitoring-api-response-collection.md) | allOf |  |
| [digital-experience-monitoring_api-response-collection-common](digital-experience-monitoring-api-response-collection-common.md) | allOf |  |
| [digital-experience-monitoring_api-response-common](digital-experience-monitoring-api-response-common.md) | object |  |
| [digital-experience-monitoring_api-response-common-failure](digital-experience-monitoring-api-response-common-failure.md) | object |  |
| [digital-experience-monitoring_api-response-single](digital-experience-monitoring-api-response-single.md) | allOf |  |
| [digital-experience-monitoring_colo](digital-experience-monitoring-colo.md) | primitive | Cloudflare colo |
| [digital-experience-monitoring_colos_response](digital-experience-monitoring-colos-response.md) | array | array of colos. |
| [digital-experience-monitoring_command_id](digital-experience-monitoring-command-id.md) | primitive | Unique identifier for a command |
| [digital-experience-monitoring_commands_devices_response](digital-experience-monitoring-commands-devices-response.md) | object |  |
| [digital-experience-monitoring_commands_users_response](digital-experience-monitoring-commands-users-response.md) | object |  |
| [digital-experience-monitoring_cpu_pct_by_app](digital-experience-monitoring-cpu-pct-by-app.md) | array |  |
| [digital-experience-monitoring_device](digital-experience-monitoring-device.md) | object |  |
| [digital-experience-monitoring_device-dex-test-schemas-data](digital-experience-monitoring-device-dex-test-schemas-data.md) | object | The configuration object which contains the detail |
| [digital-experience-monitoring_device-dex-test-schemas-description](digital-experience-monitoring-device-dex-test-schemas-description.md) | primitive | Additional details about the test. |
| [digital-experience-monitoring_device-dex-test-schemas-enabled](digital-experience-monitoring-device-dex-test-schemas-enabled.md) | primitive | Determines whether or not the test is active. |
| [digital-experience-monitoring_device-dex-test-schemas-http](digital-experience-monitoring-device-dex-test-schemas-http.md) | object |  |
| [digital-experience-monitoring_device-dex-test-schemas-interval](digital-experience-monitoring-device-dex-test-schemas-interval.md) | primitive | How often the test will run. |
| [digital-experience-monitoring_device-dex-test-schemas-name](digital-experience-monitoring-device-dex-test-schemas-name.md) | primitive | The name of the DEX test. Must be unique. |
| [digital-experience-monitoring_device-dex-test-target-policies](digital-experience-monitoring-device-dex-test-target-policies.md) | array | DEX rules targeted by this test |
| [digital-experience-monitoring_device_id](digital-experience-monitoring-device-id.md) | primitive | Device-specific ID, given as UUID v4 |
| [digital-experience-monitoring_dex-delete-response-collection](digital-experience-monitoring-dex-delete-response-collection.md) | allOf |  |
| [digital-experience-monitoring_dex-response_collection](digital-experience-monitoring-dex-response-collection.md) | allOf |  |
| [digital-experience-monitoring_dex-single_response](digital-experience-monitoring-dex-single-response.md) | allOf |  |
| [digital-experience-monitoring_dex_target_policy](digital-experience-monitoring-dex-target-policy.md) | object |  |
| [digital-experience-monitoring_fleet_status_devices_response](digital-experience-monitoring-fleet-status-devices-response.md) | allOf |  |
| [digital-experience-monitoring_fleet_status_live_response](digital-experience-monitoring-fleet-status-live-response.md) | allOf |  |
| [digital-experience-monitoring_get_commands_quota_response](digital-experience-monitoring-get-commands-quota-response.md) | object |  |
| [digital-experience-monitoring_get_commands_response](digital-experience-monitoring-get-commands-response.md) | object |  |
| [digital-experience-monitoring_http_details_percentiles_response](digital-experience-monitoring-http-details-percentiles-response.md) | object |  |
| [digital-experience-monitoring_http_details_response](digital-experience-monitoring-http-details-response.md) | object |  |
| [digital-experience-monitoring_ip_info](digital-experience-monitoring-ip-info.md) | object |  |
| [digital-experience-monitoring_live_stat](digital-experience-monitoring-live-stat.md) | object |  |
| [digital-experience-monitoring_messages](digital-experience-monitoring-messages.md) | array |  |
| [digital-experience-monitoring_mode](digital-experience-monitoring-mode.md) | primitive | The mode under which the WARP client is run |
| [digital-experience-monitoring_page](digital-experience-monitoring-page.md) | primitive | Page number of paginated results |
| [digital-experience-monitoring_per_page](digital-experience-monitoring-per-page.md) | primitive | Number of items per page |
| [digital-experience-monitoring_percentiles](digital-experience-monitoring-percentiles.md) | object |  |
| [digital-experience-monitoring_personEmail](digital-experience-monitoring-personEmail.md) | primitive | User contact email address |
| [digital-experience-monitoring_platform](digital-experience-monitoring-platform.md) | primitive | Operating system |
| [digital-experience-monitoring_post_commands_response](digital-experience-monitoring-post-commands-response.md) | object |  |
| [digital-experience-monitoring_ram_used_pct_by_app](digital-experience-monitoring-ram-used-pct-by-app.md) | array |  |
| [digital-experience-monitoring_schemas-test-id](digital-experience-monitoring-schemas-test-id.md) | primitive | The unique identifier for the test. |
| [digital-experience-monitoring_since_minutes](digital-experience-monitoring-since-minutes.md) | primitive | Number of minutes before current time |
| [digital-experience-monitoring_sort_by](digital-experience-monitoring-sort-by.md) | enum | Dimension to sort results by |
| [digital-experience-monitoring_source](digital-experience-monitoring-source.md) | enum | Specifies fleet status details source |
| [digital-experience-monitoring_status](digital-experience-monitoring-status.md) | primitive | Network status |
| [digital-experience-monitoring_test_stat_over_time](digital-experience-monitoring-test-stat-over-time.md) | object |  |
| [digital-experience-monitoring_test_stat_pct_over_time](digital-experience-monitoring-test-stat-pct-over-time.md) | object |  |
| [digital-experience-monitoring_tests_response](digital-experience-monitoring-tests-response.md) | object |  |
| [digital-experience-monitoring_time_now](digital-experience-monitoring-time-now.md) | primitive | Current time in ISO format |
| [digital-experience-monitoring_timestamp](digital-experience-monitoring-timestamp.md) | primitive | Timestamp in ISO format |
| [digital-experience-monitoring_timing_aggregates](digital-experience-monitoring-timing-aggregates.md) | object |  |
| [digital-experience-monitoring_traceroute_details_percentiles_response](digital-experience-monitoring-traceroute-details-percentiles-response.md) | object |  |
| [digital-experience-monitoring_traceroute_details_response](digital-experience-monitoring-traceroute-details-response.md) | object |  |
| [digital-experience-monitoring_traceroute_test_network_path_response](digital-experience-monitoring-traceroute-test-network-path-response.md) | object |  |
| [digital-experience-monitoring_traceroute_test_result_network_path_response](digital-experience-monitoring-traceroute-test-result-network-path-response.md) | object |  |
| [digital-experience-monitoring_uniqueDevicesTotal](digital-experience-monitoring-uniqueDevicesTotal.md) | primitive | Number of unique devices |
| [digital-experience-monitoring_unique_devices_response](digital-experience-monitoring-unique-devices-response.md) | object |  |
| [digital-experience-monitoring_uuid](digital-experience-monitoring-uuid.md) | primitive | API Resource UUID tag. |
| [digital-experience-monitoring_version](digital-experience-monitoring-version.md) | primitive | WARP client version |
| [digital-experience-monitoring_warp_config_change_event](digital-experience-monitoring-warp-config-change-event.md) | object |  |
| [digital-experience-monitoring_warp_config_details](digital-experience-monitoring-warp-config-details.md) | object |  |
| [digital-experience-monitoring_warp_events_response](digital-experience-monitoring-warp-events-response.md) | array |  |
| [digital-experience-monitoring_warp_toggle_change_event](digital-experience-monitoring-warp-toggle-change-event.md) | object |  |
