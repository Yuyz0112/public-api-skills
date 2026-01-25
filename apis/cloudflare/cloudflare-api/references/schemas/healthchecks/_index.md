# healthchecks Schemas

28 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [healthchecks_address](healthchecks-address.md) | primitive | The hostname or IP address of the origin server to |
| [healthchecks_api-response-collection](healthchecks-api-response-collection.md) | allOf |  |
| [healthchecks_api-response-common](healthchecks-api-response-common.md) | object |  |
| [healthchecks_api-response-common-failure](healthchecks-api-response-common-failure.md) | object |  |
| [healthchecks_api-response-single](healthchecks-api-response-single.md) | allOf |  |
| [healthchecks_check_regions](healthchecks-check-regions.md) | array | A list of regions from which to run health checks. |
| [healthchecks_consecutive_fails](healthchecks-consecutive-fails.md) | primitive | The number of consecutive fails required from a he |
| [healthchecks_consecutive_successes](healthchecks-consecutive-successes.md) | primitive | The number of consecutive successes required from  |
| [healthchecks_description](healthchecks-description.md) | primitive | A human-readable description of the health check. |
| [healthchecks_failure_reason](healthchecks-failure-reason.md) | primitive | The current failure reason if status is unhealthy. |
| [healthchecks_healthchecks](healthchecks-healthchecks.md) | object |  |
| [healthchecks_http_config](healthchecks-http-config.md) | object | Parameters specific to an HTTP or HTTPS health che |
| [healthchecks_id_response](healthchecks-id-response.md) | allOf |  |
| [healthchecks_identifier](healthchecks-identifier.md) | primitive | Identifier |
| [healthchecks_interval](healthchecks-interval.md) | primitive | The interval between each health check. Shorter in |
| [healthchecks_messages](healthchecks-messages.md) | array |  |
| [healthchecks_name](healthchecks-name.md) | primitive | A short name to identify the health check. Only al |
| [healthchecks_query_healthcheck](healthchecks-query-healthcheck.md) | object |  |
| [healthchecks_response_collection](healthchecks-response-collection.md) | allOf |  |
| [healthchecks_result_info](healthchecks-result-info.md) | object |  |
| [healthchecks_retries](healthchecks-retries.md) | primitive | The number of retries to attempt in case of a time |
| [healthchecks_single_response](healthchecks-single-response.md) | allOf |  |
| [healthchecks_status](healthchecks-status.md) | enum | The current status of the origin server according  |
| [healthchecks_suspended](healthchecks-suspended.md) | primitive | If suspended, no health checks are sent to the ori |
| [healthchecks_tcp_config](healthchecks-tcp-config.md) | object | Parameters specific to TCP health check. |
| [healthchecks_timeout](healthchecks-timeout.md) | primitive | The timeout (in seconds) before marking the health |
| [healthchecks_timestamp](healthchecks-timestamp.md) | primitive |  |
| [healthchecks_type](healthchecks-type.md) | primitive | The protocol to use for the health check. Currentl |
