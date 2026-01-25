# workers Schemas

145 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [workers_ErrorAuth](workers-ErrorAuth.md) | object |  |
| [workers_ErrorInternalServer](workers-ErrorInternalServer.md) | object |  |
| [workers_ErrorMissingParam](workers-ErrorMissingParam.md) | object |  |
| [workers_ErrorWorkerInvalid](workers-ErrorWorkerInvalid.md) | object |  |
| [workers_ErrorWorkerLimit](workers-ErrorWorkerLimit.md) | object |  |
| [workers_ErrorWorkerNameConflict](workers-ErrorWorkerNameConflict.md) | object |  |
| [workers_ErrorWorkerNameInvalid](workers-ErrorWorkerNameInvalid.md) | object |  |
| [workers_ErrorWorkerNamePreviewLengthLimit](workers-ErrorWorkerNamePreviewLengthLimit.md) | object |  |
| [workers_ErrorWorkerNameSubdomainLengthLimit](workers-ErrorWorkerNameSubdomainLengthLimit.md) | object |  |
| [workers_ErrorWorkerNotFound](workers-ErrorWorkerNotFound.md) | object |  |
| [workers_ErrorWorkerObservabilitySamplingRateInvalid](workers-ErrorWorkerObservabilitySamplingRateInvalid.md) | object |  |
| [workers_ErrorWorkerTagInvalid](workers-ErrorWorkerTagInvalid.md) | object |  |
| [workers_ErrorWorkerTagLengthLimit](workers-ErrorWorkerTagLengthLimit.md) | object |  |
| [workers_ErrorWorkerTagLimit](workers-ErrorWorkerTagLimit.md) | object |  |
| [workers_Version](workers-Version.md) | object |  |
| [workers_Worker](workers-Worker.md) | object |  |
| [workers_account-settings](workers-account-settings.md) | object |  |
| [workers_account_identifier](workers-account-identifier.md) | primitive | Identifer of the account. |
| [workers_api-response-collection](workers-api-response-collection.md) | allOf |  |
| [workers_api-response-common](workers-api-response-common.md) | object |  |
| [workers_api-response-common-failure](workers-api-response-common-failure.md) | object |  |
| [workers_api-response-null-result](workers-api-response-null-result.md) | allOf |  |
| [workers_api-response-single](workers-api-response-single.md) | allOf |  |
| [workers_assets](workers-assets.md) | object | Configuration for assets within a Worker. |
| [workers_binding_item](workers-binding-item.md) | oneOf | A binding to allow the Worker to communicate with  |
| [workers_binding_kind_ai](workers-binding-kind-ai.md) | object |  |
| [workers_binding_kind_analytics_engine](workers-binding-kind-analytics-engine.md) | object |  |
| [workers_binding_kind_assets](workers-binding-kind-assets.md) | object |  |
| [workers_binding_kind_browser](workers-binding-kind-browser.md) | object |  |
| [workers_binding_kind_d1](workers-binding-kind-d1.md) | object |  |
| [workers_binding_kind_data_blob](workers-binding-kind-data-blob.md) | object |  |
| [workers_binding_kind_dispatch_namespace](workers-binding-kind-dispatch-namespace.md) | object |  |
| [workers_binding_kind_durable_object_namespace](workers-binding-kind-durable-object-namespace.md) | object |  |
| [workers_binding_kind_hyperdrive](workers-binding-kind-hyperdrive.md) | object |  |
| [workers_binding_kind_images](workers-binding-kind-images.md) | object |  |
| [workers_binding_kind_inherit](workers-binding-kind-inherit.md) | object |  |
| [workers_binding_kind_json](workers-binding-kind-json.md) | object |  |
| [workers_binding_kind_kv_namespace](workers-binding-kind-kv-namespace.md) | object |  |
| [workers_binding_kind_mtls_certificate](workers-binding-kind-mtls-certificate.md) | object |  |
| [workers_binding_kind_pipelines](workers-binding-kind-pipelines.md) | object |  |
| [workers_binding_kind_plain_text](workers-binding-kind-plain-text.md) | object |  |
| [workers_binding_kind_queue](workers-binding-kind-queue.md) | object |  |
| [workers_binding_kind_r2_bucket](workers-binding-kind-r2-bucket.md) | object |  |
| [workers_binding_kind_secret_key](workers-binding-kind-secret-key.md) | object |  |
| [workers_binding_kind_secret_text](workers-binding-kind-secret-text.md) | object |  |
| [workers_binding_kind_secrets_store_secret](workers-binding-kind-secrets-store-secret.md) | object |  |
| [workers_binding_kind_send_email](workers-binding-kind-send-email.md) | object |  |
| [workers_binding_kind_service](workers-binding-kind-service.md) | object |  |
| [workers_binding_kind_text_blob](workers-binding-kind-text-blob.md) | object |  |
| [workers_binding_kind_vectorize](workers-binding-kind-vectorize.md) | object |  |
| [workers_binding_kind_version_metadata](workers-binding-kind-version-metadata.md) | object |  |
| [workers_binding_kind_wasm_module](workers-binding-kind-wasm-module.md) | object |  |
| [workers_binding_kind_workflow](workers-binding-kind-workflow.md) | object |  |
| [workers_binding_name](workers-binding-name.md) | primitive | A JavaScript variable name for the binding. |
| [workers_bindings](workers-bindings.md) | array | List of bindings attached to a Worker. You can fin |
| [workers_compatibility_date](workers-compatibility-date.md) | primitive | Date indicating targeted support in the Workers ru |
| [workers_compatibility_flag](workers-compatibility-flag.md) | primitive | Flag that enables or disables a specific feature i |
| [workers_compatibility_flags](workers-compatibility-flags.md) | array | Flags that enable or disable certain features in t |
| [workers_completed-upload-assets-response](workers-completed-upload-assets-response.md) | allOf |  |
| [workers_create-assets-upload-session-object](workers-create-assets-upload-session-object.md) | object |  |
| [workers_create-assets-upload-session-response](workers-create-assets-upload-session-response.md) | allOf |  |
| [workers_created_on](workers-created-on.md) | primitive | When the script was created. |
| [workers_cursor](workers-cursor.md) | primitive | Opaque token indicating the position from which to |
| [workers_deployment](workers-deployment.md) | object |  |
| [workers_dispatch_namespace_name](workers-dispatch-namespace-name.md) | primitive | Name of the Workers for Platforms dispatch namespa |
| [workers_domain](workers-domain.md) | object |  |
| [workers_domain-response-collection](workers-domain-response-collection.md) | allOf |  |
| [workers_domain-response-single](workers-domain-response-single.md) | allOf |  |
| [workers_domain_identifier](workers-domain-identifier.md) | primitive | Identifer of the Worker Domain. |
| [workers_environment](workers-environment.md) | primitive | Optional environment if the Worker utilizes one. |
| [workers_etag](workers-etag.md) | primitive | Hashed script content, can be used in a If-None-Ma |
| [workers_has_assets](workers-has-assets.md) | primitive | Whether a Worker contains assets. |
| [workers_has_modules](workers-has-modules.md) | primitive | Whether a Worker contains modules. |
| [workers_hostname](workers-hostname.md) | primitive | Hostname of the Worker Domain. |
| [workers_identifier](workers-identifier.md) | primitive | Identifier. |
| [workers_limits](workers-limits.md) | object | Limits to apply for this Worker. |
| [workers_logpush](workers-logpush.md) | primitive | Whether Logpush is turned on for the Worker. |
| [workers_manifest-value](workers-manifest-value.md) | object |  |
| [workers_messages](workers-messages.md) | array |  |
| [workers_migration_step](workers-migration-step.md) | object |  |
| [workers_migration_tag_conditions](workers-migration-tag-conditions.md) | object |  |
| [workers_modified_on](workers-modified-on.md) | primitive | When the script was last modified. |
| [workers_multipart-script](workers-multipart-script.md) | object |  |
| [workers_multiple_step_migrations](workers-multiple-step-migrations.md) | allOf |  |
| [workers_namespace](workers-namespace.md) | object |  |
| [workers_namespace-list-response](workers-namespace-list-response.md) | allOf |  |
| [workers_namespace-response](workers-namespace-response.md) | object |  |
| [workers_namespace-script-delete-bulk-response](workers-namespace-script-delete-bulk-response.md) | object | Detail about bulk deletion of scripts in a namespa |
| [workers_namespace-script-response](workers-namespace-script-response.md) | object | Details about a worker uploaded to a Workers for P |
| [workers_namespace-script-response-single](workers-namespace-script-response-single.md) | allOf |  |
| [workers_namespace-single-response](workers-namespace-single-response.md) | allOf |  |
| [workers_namespace_identifier](workers-namespace-identifier.md) | primitive | Namespace identifier tag. |
| [workers_object](workers-object.md) | object |  |
| [workers_observability](workers-observability.md) | object | Observability settings for the Worker. |
| [workers_placement-provider](workers-placement-provider.md) | object |  |
| [workers_placement-region](workers-placement-region.md) | object |  |
| [workers_placement-regions-response](workers-placement-regions-response.md) | object |  |
| [workers_placement_info](workers-placement-info.md) | allOf | Configuration for [Smart Placement](https://develo |
| [workers_placement_info_no_status](workers-placement-info-no-status.md) | oneOf | Configuration for [Smart Placement](https://develo |
| [workers_placement_mode](workers-placement-mode.md) | enum | Enables [Smart Placement](https://developers.cloud |
| [workers_placement_status](workers-placement-status.md) | enum | Status of [Smart Placement](https://developers.clo |
| [workers_route](workers-route.md) | object |  |
| [workers_schedule](workers-schedule.md) | object |  |
| [workers_schemas-environment](workers-schemas-environment.md) | primitive | Worker environment associated with the zone and ho |
| [workers_schemas-id](workers-schemas-id.md) | primitive | ID of the namespace. |
| [workers_schemas-script_name](workers-schemas-script-name.md) | primitive | Name of the script. |
| [workers_schemas-service](workers-schemas-service.md) | primitive | Worker service associated with the zone and hostna |
| [workers_schemas-subdomain](workers-schemas-subdomain.md) | object |  |
| [workers_script-and-version-settings-item](workers-script-and-version-settings-item.md) | object |  |
| [workers_script-and-version-settings-response](workers-script-and-version-settings-response.md) | allOf |  |
| [workers_script-response](workers-script-response.md) | object |  |
| [workers_script-response-collection](workers-script-response-collection.md) | allOf |  |
| [workers_script-response-single](workers-script-response-single.md) | allOf |  |
| [workers_script-response-upload](workers-script-response-upload.md) | allOf |  |
| [workers_script-response-upload-single](workers-script-response-upload-single.md) | allOf |  |
| [workers_script-settings-item](workers-script-settings-item.md) | object |  |
| [workers_script-settings-response](workers-script-settings-response.md) | allOf |  |
| [workers_script_count](workers-script-count.md) | primitive | The current number of scripts in this Dispatch Nam |
| [workers_script_name](workers-script-name.md) | primitive | Name of the script, used in URLs and route configu |
| [workers_secret](workers-secret.md) | oneOf | A secret value accessible through a binding. |
| [workers_secret_name](workers-secret-name.md) | primitive | A JavaScript variable name for the secret binding. |
| [workers_secret_name_url_encoded](workers-secret-name-url-encoded.md) | primitive | Flag that indicates whether the secret name is URL |
| [workers_service](workers-service.md) | primitive | Name of Worker to bind to. |
| [workers_single_step_migrations](workers-single-step-migrations.md) | allOf | A single set of migrations to apply. |
| [workers_subdomain](workers-subdomain.md) | object |  |
| [workers_tag](workers-tag.md) | primitive |  |
| [workers_tags](workers-tags.md) | array | Tags associated with the Worker. |
| [workers_tail](workers-tail.md) | object |  |
| [workers_tail_consumers](workers-tail-consumers.md) | array | List of Workers that will consume logs from the at |
| [workers_tail_consumers_script](workers-tail-consumers-script.md) | object | A reference to a script that will consume logs fro |
| [workers_trusted_workers](workers-trusted-workers.md) | primitive | Whether the Workers in the namespace are executed  |
| [workers_upload-assets-response](workers-upload-assets-response.md) | allOf |  |
| [workers_usage-model-response](workers-usage-model-response.md) | allOf |  |
| [workers_usage_model](workers-usage-model.md) | enum | Usage model for the Worker invocations. |
| [workers_user_limits](workers-user-limits.md) | object | User-defined resource limits for Workers with stan |
| [workers_uuid](workers-uuid.md) | primitive | API Resource UUID tag. |
| [workers_version-item-full](workers-version-item-full.md) | allOf |  |
| [workers_version-item-short](workers-version-item-short.md) | object |  |
| [workers_version-item-uploaded](workers-version-item-uploaded.md) | allOf |  |
| [workers_version_identifier](workers-version-identifier.md) | primitive |  |
| [workers_versions-list-response](workers-versions-list-response.md) | allOf |  |
| [workers_versions-single-response](workers-versions-single-response.md) | allOf |  |
| [workers_versions-upload-response](workers-versions-upload-response.md) | allOf |  |
| [workers_zone_identifier](workers-zone-identifier.md) | primitive | Identifier of the zone. |
| [workers_zone_name](workers-zone-name.md) | primitive | Name of the zone. |
