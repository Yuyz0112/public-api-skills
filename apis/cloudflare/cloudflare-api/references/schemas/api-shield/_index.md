# api-shield Schemas

120 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [api-shield_Rule](api-shield-Rule.md) | object | A Token Validation rule that can enforce security  |
| [api-shield_TokenConfiguration](api-shield-TokenConfiguration.md) | object |  |
| [api-shield_action](api-shield-action.md) | enum | Action to take on requests that match operations i |
| [api-shield_after](api-shield-after.md) | object | Move rule to before rule with ID. |
| [api-shield_api-response-collection](api-shield-api-response-collection.md) | allOf |  |
| [api-shield_api-response-common](api-shield-api-response-common.md) | object |  |
| [api-shield_api-response-common-failure](api-shield-api-response-common-failure.md) | object |  |
| [api-shield_api-response-single](api-shield-api-response-single.md) | allOf |  |
| [api-shield_api-response-single-obj](api-shield-api-response-single-obj.md) | allOf |  |
| [api-shield_api_discovery_origin](api-shield-api-discovery-origin.md) | enum | * `ML` - Discovered operation was sourced using ML |
| [api-shield_api_discovery_patch_multiple_request](api-shield-api-discovery-patch-multiple-request.md) | object |  |
| [api-shield_api_discovery_patch_multiple_request_entry](api-shield-api-discovery-patch-multiple-request-entry.md) | object | Mappings of discovered operations (keys) to object |
| [api-shield_api_discovery_state](api-shield-api-discovery-state.md) | enum | State of operation in API Discovery
  * `review` - |
| [api-shield_api_discovery_state_patch](api-shield-api-discovery-state-patch.md) | enum | Mark state of operation in API Discovery
  * `revi |
| [api-shield_auth_id_characteristic](api-shield-auth-id-characteristic.md) | object | Auth ID Characteristic |
| [api-shield_auth_id_characteristic_jwt_claim](api-shield-auth-id-characteristic-jwt-claim.md) | object | Auth ID Characteristic extracted from JWT Token Cl |
| [api-shield_auth_id_characteristics](api-shield-auth-id-characteristics.md) | array |  |
| [api-shield_auth_id_tokens](api-shield-auth-id-tokens.md) | primitive | The total number of auth-ids seen across this calc |
| [api-shield_basic_operation](api-shield-basic-operation.md) | object |  |
| [api-shield_before](api-shield-before.md) | object | Move rule to after rule with ID. |
| [api-shield_confidence_intervals_bounds](api-shield-confidence-intervals-bounds.md) | object | Upper and lower bound for percentile estimate |
| [api-shield_configuration](api-shield-configuration.md) | object |  |
| [api-shield_configuration-single-response](api-shield-configuration-single-response.md) | allOf |  |
| [api-shield_cookie](api-shield-cookie.md) | primitive | HTTP request cookie |
| [api-shield_create-single-rule-request](api-shield-create-single-rule-request.md) | allOf |  |
| [api-shield_credentials](api-shield-credentials.md) | object |  |
| [api-shield_credentials-JWT-Key](api-shield-credentials-JWT-Key.md) | oneOf | JSON representation of a JWKS key. |
| [api-shield_credentials-JWT-Key-EC-ES256](api-shield-credentials-JWT-Key-EC-ES256.md) | allOf | JSON representation of an ES256 key |
| [api-shield_credentials-JWT-Key-EC-ES384](api-shield-credentials-JWT-Key-EC-ES384.md) | allOf | JSON representation of an ES384 key |
| [api-shield_credentials-JWT-Key-EC-common](api-shield-credentials-JWT-Key-EC-common.md) | object |  |
| [api-shield_credentials-JWT-Key-RSA](api-shield-credentials-JWT-Key-RSA.md) | allOf | JSON representation of an RSA key. |
| [api-shield_credentials-JWT-Key-common](api-shield-credentials-JWT-Key-common.md) | object |  |
| [api-shield_data_points](api-shield-data-points.md) | primitive | The number of data points used for the threshold s |
| [api-shield_description](api-shield-description.md) | primitive |  |
| [api-shield_discovery_operation](api-shield-discovery-operation.md) | allOf |  |
| [api-shield_edit-single-rule-request](api-shield-edit-single-rule-request.md) | allOf |  |
| [api-shield_enabled](api-shield-enabled.md) | primitive | Toggle rule on or off. |
| [api-shield_endpoint](api-shield-endpoint.md) | primitive | The endpoint which can contain path parameter temp |
| [api-shield_expression](api-shield-expression.md) | primitive | Rule expression. Requests that fail to match this  |
| [api-shield_global_setting_change_base](api-shield-global-setting-change-base.md) | object |  |
| [api-shield_global_settings](api-shield-global-settings.md) | object |  |
| [api-shield_header](api-shield-header.md) | primitive | HTTP request header (must be lowercase) |
| [api-shield_host](api-shield-host.md) | primitive | RFC3986-compliant host. |
| [api-shield_identifier](api-shield-identifier.md) | primitive | Identifier. |
| [api-shield_index](api-shield-index.md) | object |  |
| [api-shield_messages](api-shield-messages.md) | array |  |
| [api-shield_method](api-shield-method.md) | enum | The HTTP method used to access the endpoint. |
| [api-shield_multiple-operation-response](api-shield-multiple-operation-response.md) | allOf |  |
| [api-shield_multiple-operation-response-paginated](api-shield-multiple-operation-response-paginated.md) | allOf |  |
| [api-shield_object-with-operation-id](api-shield-object-with-operation-id.md) | object |  |
| [api-shield_old_kind](api-shield-old-kind.md) | enum | Kind of schema |
| [api-shield_old_operation_mitigation_action](api-shield-old-operation-mitigation-action.md) | enum | When set, this applies a mitigation action to this |
| [api-shield_old_operation_schema_validation_settings](api-shield-old-operation-schema-validation-settings.md) | object |  |
| [api-shield_old_operation_schema_validation_settings_modify_request](api-shield-old-operation-schema-validation-settings-modify-request.md) | object |  |
| [api-shield_old_operation_schema_validation_settings_multiple_request](api-shield-old-operation-schema-validation-settings-multiple-request.md) | object |  |
| [api-shield_old_operation_schema_validation_settings_multiple_request_entry](api-shield-old-operation-schema-validation-settings-multiple-request-entry.md) | object | Operation ID to mitigation action mappings |
| [api-shield_old_public_schema](api-shield-old-public-schema.md) | object |  |
| [api-shield_old_response_user_schemas_hosts](api-shield-old-response-user-schemas-hosts.md) | object |  |
| [api-shield_old_schema_upload_details_errors_critical](api-shield-old-schema-upload-details-errors-critical.md) | object |  |
| [api-shield_old_schema_upload_details_warnings_only](api-shield-old-schema-upload-details-warnings-only.md) | object |  |
| [api-shield_old_schema_upload_failure](api-shield-old-schema-upload-failure.md) | allOf |  |
| [api-shield_old_schema_upload_log_event](api-shield-old-schema-upload-log-event.md) | object |  |
| [api-shield_old_schema_upload_response](api-shield-old-schema-upload-response.md) | object |  |
| [api-shield_old_validation_default_mitigation_action](api-shield-old-validation-default-mitigation-action.md) | enum | The default mitigation action used when there is n |
| [api-shield_old_validation_default_mitigation_action_patch](api-shield-old-validation-default-mitigation-action-patch.md) | enum | The default mitigation action used when there is n |
| [api-shield_old_validation_enabled](api-shield-old-validation-enabled.md) | primitive | Flag whether schema is enabled for validation. |
| [api-shield_old_validation_override_mitigation_action](api-shield-old-validation-override-mitigation-action.md) | enum | When set, this overrides both zone level and opera |
| [api-shield_old_validation_override_mitigation_action_patch](api-shield-old-validation-override-mitigation-action-patch.md) | enum | When set, this overrides both zone level and opera |
| [api-shield_old_validation_override_mitigation_action_write](api-shield-old-validation-override-mitigation-action-write.md) | enum | When set, this overrides both zone level and opera |
| [api-shield_old_zone_schema_validation_settings](api-shield-old-zone-schema-validation-settings.md) | object |  |
| [api-shield_old_zone_schema_validation_settings_patch](api-shield-old-zone-schema-validation-settings-patch.md) | object |  |
| [api-shield_old_zone_schema_validation_settings_put](api-shield-old-zone-schema-validation-settings-put.md) | object |  |
| [api-shield_openapi](api-shield-openapi.md) | object | A OpenAPI 3.0.0 compliant schema. |
| [api-shield_openapi-with-thresholds](api-shield-openapi-with-thresholds.md) | object | A OpenAPI 3.0.0 compliant schema. |
| [api-shield_operation](api-shield-operation.md) | allOf |  |
| [api-shield_operation_feature_api_routing](api-shield-operation-feature-api-routing.md) | object |  |
| [api-shield_operation_feature_confidence_intervals](api-shield-operation-feature-confidence-intervals.md) | object |  |
| [api-shield_operation_feature_parameter_schemas](api-shield-operation-feature-parameter-schemas.md) | object |  |
| [api-shield_operation_feature_schema_info](api-shield-operation-feature-schema-info.md) | object |  |
| [api-shield_operation_feature_thresholds](api-shield-operation-feature-thresholds.md) | object |  |
| [api-shield_operation_features](api-shield-operation-features.md) | anyOf |  |
| [api-shield_p50](api-shield-p50.md) | primitive | The p50 quantile of requests (in period_seconds). |
| [api-shield_p90](api-shield-p90.md) | primitive | The p90 quantile of requests (in period_seconds). |
| [api-shield_p99](api-shield-p99.md) | primitive | The p99 quantile of requests (in period_seconds). |
| [api-shield_parameter_schemas_definition](api-shield-parameter-schemas-definition.md) | object | An operation schema object containing a response. |
| [api-shield_patch_discoveries_response](api-shield-patch-discoveries-response.md) | allOf |  |
| [api-shield_patch_discovery_response](api-shield-patch-discovery-response.md) | allOf |  |
| [api-shield_per_operation_bulk_settings](api-shield-per-operation-bulk-settings.md) | object | Operation ID to per operation setting mapping |
| [api-shield_per_operation_setting](api-shield-per-operation-setting.md) | object |  |
| [api-shield_per_operation_setting_change_base](api-shield-per-operation-setting-change-base.md) | object |  |
| [api-shield_period_seconds](api-shield-period-seconds.md) | primitive | The period over which this threshold is suggested. |
| [api-shield_position](api-shield-position.md) | oneOf | Update rule order among zone rules. |
| [api-shield_public_schema](api-shield-public-schema.md) | object | A schema used in schema validation |
| [api-shield_public_schema_success_result](api-shield-public-schema-success-result.md) | allOf |  |
| [api-shield_request_expression_templates_fallthrough](api-shield-request-expression-templates-fallthrough.md) | object |  |
| [api-shield_requests](api-shield-requests.md) | primitive | The estimated number of requests covered by these  |
| [api-shield_response_expression_templates_fallthrough](api-shield-response-expression-templates-fallthrough.md) | object |  |
| [api-shield_rule-properties](api-shield-rule-properties.md) | object |  |
| [api-shield_schema-response-with-thresholds](api-shield-schema-response-with-thresholds.md) | allOf |  |
| [api-shield_schema_hosts](api-shield-schema-hosts.md) | object |  |
| [api-shield_schema_issue_notification](api-shield-schema-issue-notification.md) | object |  |
| [api-shield_schema_response_discovery](api-shield-schema-response-discovery.md) | allOf |  |
| [api-shield_schemas-description](api-shield-schemas-description.md) | primitive | A human-readable description that gives more detai |
| [api-shield_schemas-identifier](api-shield-schemas-identifier.md) | allOf |  |
| [api-shield_schemas-timestamp](api-shield-schemas-timestamp.md) | allOf |  |
| [api-shield_schemas-title](api-shield-schemas-title.md) | primitive | A human-readable name for the rule. |
| [api-shield_schemas-uuid](api-shield-schemas-uuid.md) | allOf |  |
| [api-shield_selector](api-shield-selector.md) | object | Select operations covered by this rule.

For detai |
| [api-shield_selector-exclude](api-shield-selector-exclude.md) | object |  |
| [api-shield_selector-include](api-shield-selector-include.md) | object |  |
| [api-shield_selector-operation-state](api-shield-selector-operation-state.md) | enum | Details how `selector` interacted with an operatio |
| [api-shield_single-operation-response](api-shield-single-operation-response.md) | allOf |  |
| [api-shield_standard_operation](api-shield-standard-operation.md) | allOf |  |
| [api-shield_suggested_threshold](api-shield-suggested-threshold.md) | primitive | The suggested threshold in requests done by the sa |
| [api-shield_timestamp](api-shield-timestamp.md) | primitive |  |
| [api-shield_title](api-shield-title.md) | primitive |  |
| [api-shield_token_sources](api-shield-token-sources.md) | array |  |
| [api-shield_token_type](api-shield-token-type.md) | enum |  |
| [api-shield_traffic_stats](api-shield-traffic-stats.md) | object |  |
| [api-shield_uuid](api-shield-uuid.md) | primitive | UUID. |
