# aaa Schemas

77 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [aaa_account-id](aaa-account-id.md) | primitive | The account id |
| [aaa_alert-types](aaa-alert-types.md) | object |  |
| [aaa_alert_body](aaa-alert-body.md) | primitive | Message body included in the notification sent. |
| [aaa_alert_interval](aaa-alert-interval.md) | primitive | Optional specification of how often to re-alert fr |
| [aaa_alert_type](aaa-alert-type.md) | enum | Refers to which event will trigger a Notification  |
| [aaa_alerts-response_collection](aaa-alerts-response-collection.md) | allOf |  |
| [aaa_api-response-collection](aaa-api-response-collection.md) | allOf |  |
| [aaa_api-response-common](aaa-api-response-common.md) | object |  |
| [aaa_api-response-common-failure](aaa-api-response-common-failure.md) | object |  |
| [aaa_api-response-single](aaa-api-response-single.md) | allOf |  |
| [aaa_audit-logs](aaa-audit-logs.md) | object |  |
| [aaa_audit-logs-v2](aaa-audit-logs-v2.md) | object |  |
| [aaa_audit-logs-v2-response-collection](aaa-audit-logs-v2-response-collection.md) | object |  |
| [aaa_audit_logs_response_collection](aaa-audit-logs-response-collection.md) | oneOf |  |
| [aaa_before](aaa-before.md) | primitive | Limit the returned results to history records olde |
| [aaa_components-schemas-api-response-common-failure](aaa-components-schemas-api-response-common-failure.md) | object |  |
| [aaa_components-schemas-description](aaa-components-schemas-description.md) | primitive | Description of the notification policy (if present |
| [aaa_components-schemas-messages](aaa-components-schemas-messages.md) | array |  |
| [aaa_components-schemas-name](aaa-components-schemas-name.md) | primitive | The name of the webhook destination. This will be  |
| [aaa_components-schemas-response_collection](aaa-components-schemas-response-collection.md) | allOf |  |
| [aaa_components-schemas-type](aaa-components-schemas-type.md) | enum | Type of webhook endpoint. |
| [aaa_created_at](aaa-created-at.md) | primitive | Timestamp of when the webhook destination was crea |
| [aaa_description](aaa-description.md) | primitive | Describes the alert type. |
| [aaa_display_name](aaa-display-name.md) | primitive | Alert type name. |
| [aaa_eligibility](aaa-eligibility.md) | object |  |
| [aaa_eligible](aaa-eligible.md) | primitive | Determines whether or not the account is eligible  |
| [aaa_enabled](aaa-enabled.md) | primitive | Whether or not the Notification policy is enabled. |
| [aaa_filter_options](aaa-filter-options.md) | array | Format of additional configuration options (filter |
| [aaa_filters](aaa-filters.md) | object | Optional filters that allow you to be alerted only |
| [aaa_history](aaa-history.md) | object |  |
| [aaa_history_components-schemas-response_collection](aaa-history-components-schemas-response-collection.md) | allOf |  |
| [aaa_id_response](aaa-id-response.md) | allOf |  |
| [aaa_identifier](aaa-identifier.md) | primitive | Identifier |
| [aaa_integration-token](aaa-integration-token.md) | primitive | The token integration key |
| [aaa_last_failure](aaa-last-failure.md) | primitive | Timestamp of the last time an attempt to dispatch  |
| [aaa_last_success](aaa-last-success.md) | primitive | Timestamp of the last time Cloudflare was able to  |
| [aaa_mechanism](aaa-mechanism.md) | primitive | The mechanism to which the notification has been d |
| [aaa_mechanism_type](aaa-mechanism-type.md) | enum | The type of mechanism to which the notification ha |
| [aaa_mechanisms](aaa-mechanisms.md) | object | List of IDs that will be used when dispatching a n |
| [aaa_messages](aaa-messages.md) | array |  |
| [aaa_name](aaa-name.md) | primitive | The name of the pagerduty service. |
| [aaa_pagerduty](aaa-pagerduty.md) | object |  |
| [aaa_per_page](aaa-per-page.md) | primitive | Number of items per page. |
| [aaa_policies](aaa-policies.md) | object |  |
| [aaa_policies_components-schemas-response_collection](aaa-policies-components-schemas-response-collection.md) | allOf |  |
| [aaa_policy-id](aaa-policy-id.md) | primitive | The unique identifier of a notification policy |
| [aaa_ready](aaa-ready.md) | primitive | Beta flag. Users can create a policy with a mechan |
| [aaa_result_info](aaa-result-info.md) | object | Provides information about the result of the reque |
| [aaa_schemas-alert_type](aaa-schemas-alert-type.md) | primitive | Type of notification that has been dispatched. |
| [aaa_schemas-api-response-common](aaa-schemas-api-response-common.md) | object |  |
| [aaa_schemas-api-response-common-failure](aaa-schemas-api-response-common-failure.md) | object |  |
| [aaa_schemas-description](aaa-schemas-description.md) | primitive | Optional description for the Notification policy. |
| [aaa_schemas-identifier](aaa-schemas-identifier.md) | primitive | A unique identifier for the audit log entry. |
| [aaa_schemas-messages](aaa-schemas-messages.md) | array |  |
| [aaa_schemas-name](aaa-schemas-name.md) | primitive | Name of the policy. |
| [aaa_schemas-response_collection](aaa-schemas-response-collection.md) | allOf |  |
| [aaa_schemas-result_info](aaa-schemas-result-info.md) | object |  |
| [aaa_schemas-single_response](aaa-schemas-single-response.md) | allOf |  |
| [aaa_schemas-type](aaa-schemas-type.md) | enum | Determines type of delivery mechanism. |
| [aaa_secret](aaa-secret.md) | primitive | Optional secret that will be passed in the `cf-web |
| [aaa_sensitive_id_response](aaa-sensitive-id-response.md) | allOf |  |
| [aaa_sent](aaa-sent.md) | primitive | Timestamp of when the notification was dispatched  |
| [aaa_silence](aaa-silence.md) | object |  |
| [aaa_silence-id](aaa-silence-id.md) | primitive | Silence ID |
| [aaa_silence_components-schemas-response_collection](aaa-silence-components-schemas-response-collection.md) | allOf |  |
| [aaa_silence_create_request](aaa-silence-create-request.md) | object |  |
| [aaa_silence_update_request](aaa-silence-update-request.md) | object |  |
| [aaa_silences_components-schemas-response_collection](aaa-silences-components-schemas-response-collection.md) | allOf |  |
| [aaa_single_response](aaa-single-response.md) | allOf |  |
| [aaa_timestamp](aaa-timestamp.md) | primitive |  |
| [aaa_token](aaa-token.md) | primitive | token in form of UUID |
| [aaa_type](aaa-type.md) | primitive | Use this value when creating and updating a notifi |
| [aaa_url](aaa-url.md) | primitive | The POST endpoint to call when dispatching a notif |
| [aaa_uuid](aaa-uuid.md) | primitive | UUID |
| [aaa_webhook-id](aaa-webhook-id.md) | primitive | The unique identifier of a webhook |
| [aaa_webhooks](aaa-webhooks.md) | object |  |
| [aaa_webhooks_components-schemas-response_collection](aaa-webhooks-components-schemas-response-collection.md) | allOf |  |
