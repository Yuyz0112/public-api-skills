# logpush Schemas

38 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [logpush_api-response-common](logpush-api-response-common.md) | object |  |
| [logpush_api-response-common-failure](logpush-api-response-common-failure.md) | object |  |
| [logpush_api-response-single](logpush-api-response-single.md) | allOf |  |
| [logpush_dataset](logpush-dataset.md) | enum | Name of the dataset. A list of supported datasets  |
| [logpush_destination_conf](logpush-destination-conf.md) | primitive | Uniquely identifies a resource (such as an s3 buck |
| [logpush_destination_exists_response](logpush-destination-exists-response.md) | allOf |  |
| [logpush_enabled](logpush-enabled.md) | primitive | Flag that indicates if the job is enabled. |
| [logpush_error_message](logpush-error-message.md) | primitive | If not null, the job is currently failing. Failure |
| [logpush_fields](logpush-fields.md) | primitive | Comma-separated list of fields. |
| [logpush_filter](logpush-filter.md) | primitive | The filters to select the events to include and/or |
| [logpush_frequency](logpush-frequency.md) | enum | This field is deprecated. Please use `max_upload_* |
| [logpush_get_ownership_response](logpush-get-ownership-response.md) | allOf |  |
| [logpush_id](logpush-id.md) | primitive | Unique id of the job. |
| [logpush_identifier](logpush-identifier.md) | primitive | Identifier. |
| [logpush_instant_logs_job](logpush-instant-logs-job.md) | object |  |
| [logpush_instant_logs_job_response_collection](logpush-instant-logs-job-response-collection.md) | allOf |  |
| [logpush_instant_logs_job_response_single](logpush-instant-logs-job-response-single.md) | allOf |  |
| [logpush_kind](logpush-kind.md) | enum | The kind parameter (optional) is used to different |
| [logpush_last_complete](logpush-last-complete.md) | primitive | Records the last time for which logs have been suc |
| [logpush_last_error](logpush-last-error.md) | primitive | Records the last time the job failed. If not null, |
| [logpush_logpull_options](logpush-logpull-options.md) | primitive | This field is deprecated. Use `output_options` ins |
| [logpush_logpush_field_response_collection](logpush-logpush-field-response-collection.md) | allOf |  |
| [logpush_logpush_job](logpush-logpush-job.md) | object |  |
| [logpush_logpush_job_response_collection](logpush-logpush-job-response-collection.md) | allOf |  |
| [logpush_logpush_job_response_single](logpush-logpush-job-response-single.md) | allOf |  |
| [logpush_max_upload_bytes](logpush-max-upload-bytes.md) | oneOf | The maximum uncompressed file size of a batch of l |
| [logpush_max_upload_interval_seconds](logpush-max-upload-interval-seconds.md) | oneOf | The maximum interval in seconds for log batches. T |
| [logpush_max_upload_records](logpush-max-upload-records.md) | oneOf | The maximum number of log lines per batch. This se |
| [logpush_messages](logpush-messages.md) | array |  |
| [logpush_name](logpush-name.md) | primitive | Optional human readable job name. Not unique. Clou |
| [logpush_output_options](logpush-output-options.md) | object | The structured replacement for `logpull_options`.  |
| [logpush_ownership_challenge](logpush-ownership-challenge.md) | primitive | Ownership challenge token to prove destination own |
| [logpush_sample](logpush-sample.md) | primitive | The sample parameter is the sample rate of the rec |
| [logpush_schemas-destination_conf](logpush-schemas-destination-conf.md) | primitive | Unique WebSocket address that will receive message |
| [logpush_schemas-filter](logpush-schemas-filter.md) | primitive | Filters to drill down into specific events. |
| [logpush_session_id](logpush-session-id.md) | primitive | Unique session id of the job. |
| [logpush_validate_ownership_response](logpush-validate-ownership-response.md) | allOf |  |
| [logpush_validate_response](logpush-validate-response.md) | allOf |  |
