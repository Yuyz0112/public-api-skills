# R2 Bucket

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/event_notifications/r2/{bucket_name}/configuration` | List Event Notification Rules | [View](../operations/r2-get-event-notification-configs.md) |
| GET | `/accounts/{account_id}/event_notifications/r2/{bucket_name}/configuration/queues/{queue_id}` | Get Event Notification Rule | [View](../operations/r2-get-event-notification-config.md) |
| PUT | `/accounts/{account_id}/event_notifications/r2/{bucket_name}/configuration/queues/{queue_id}` | Create Event Notification Rule | [View](../operations/r2-put-event-notification-config.md) |
| DELETE | `/accounts/{account_id}/event_notifications/r2/{bucket_name}/configuration/queues/{queue_id}` | Delete Event Notification Rules | [View](../operations/r2-event-notification-delete-config.md) |
| GET | `/accounts/{account_id}/r2/buckets` | List Buckets | [View](../operations/r2-list-buckets.md) |
| POST | `/accounts/{account_id}/r2/buckets` | Create Bucket | [View](../operations/r2-create-bucket.md) |
| GET | `/accounts/{account_id}/r2/buckets/{bucket_name}` | Get Bucket | [View](../operations/r2-get-bucket.md) |
| DELETE | `/accounts/{account_id}/r2/buckets/{bucket_name}` | Delete Bucket | [View](../operations/r2-delete-bucket.md) |
| PATCH | `/accounts/{account_id}/r2/buckets/{bucket_name}` | Patch Bucket | [View](../operations/r2-patch-bucket.md) |
| GET | `/accounts/{account_id}/r2/buckets/{bucket_name}/cors` | Get Bucket CORS Policy | [View](../operations/r2-get-bucket-cors-policy.md) |
| PUT | `/accounts/{account_id}/r2/buckets/{bucket_name}/cors` | Put Bucket CORS Policy | [View](../operations/r2-put-bucket-cors-policy.md) |
| DELETE | `/accounts/{account_id}/r2/buckets/{bucket_name}/cors` | Delete Bucket CORS Policy | [View](../operations/r2-delete-bucket-cors-policy.md) |
| GET | `/accounts/{account_id}/r2/buckets/{bucket_name}/domains/custom` | List Custom Domains of Bucket | [View](../operations/r2-list-custom-domains.md) |
| POST | `/accounts/{account_id}/r2/buckets/{bucket_name}/domains/custom` | Attach Custom Domain To Bucket | [View](../operations/r2-add-custom-domain.md) |
| GET | `/accounts/{account_id}/r2/buckets/{bucket_name}/domains/custom/{domain}` | Get Custom Domain Settings | [View](../operations/r2-get-custom-domain-settings.md) |
| PUT | `/accounts/{account_id}/r2/buckets/{bucket_name}/domains/custom/{domain}` | Configure Custom Domain Settings | [View](../operations/r2-edit-custom-domain-settings.md) |
| DELETE | `/accounts/{account_id}/r2/buckets/{bucket_name}/domains/custom/{domain}` | Remove Custom Domain From Bucket | [View](../operations/r2-delete-custom-domain.md) |
| GET | `/accounts/{account_id}/r2/buckets/{bucket_name}/domains/managed` | Get r2.dev Domain of Bucket | [View](../operations/r2-get-bucket-public-policy.md) |
| PUT | `/accounts/{account_id}/r2/buckets/{bucket_name}/domains/managed` | Update r2.dev Domain of Bucket | [View](../operations/r2-put-bucket-public-policy.md) |
| GET | `/accounts/{account_id}/r2/buckets/{bucket_name}/lifecycle` | Get Object Lifecycle Rules | [View](../operations/r2-get-bucket-lifecycle-configuration.md) |
| PUT | `/accounts/{account_id}/r2/buckets/{bucket_name}/lifecycle` | Put Object Lifecycle Rules | [View](../operations/r2-put-bucket-lifecycle-configuration.md) |
| GET | `/accounts/{account_id}/r2/buckets/{bucket_name}/lock` | Get Bucket Lock Rules | [View](../operations/r2-get-bucket-lock-configuration.md) |
| PUT | `/accounts/{account_id}/r2/buckets/{bucket_name}/lock` | Put Bucket Lock Rules | [View](../operations/r2-put-bucket-lock-configuration.md) |
| GET | `/accounts/{account_id}/r2/buckets/{bucket_name}/sippy` | Get Sippy Configuration | [View](../operations/r2-get-bucket-sippy-config.md) |
| PUT | `/accounts/{account_id}/r2/buckets/{bucket_name}/sippy` | Enable Sippy | [View](../operations/r2-put-bucket-sippy-config.md) |
| DELETE | `/accounts/{account_id}/r2/buckets/{bucket_name}/sippy` | Disable Sippy | [View](../operations/r2-delete-bucket-sippy-config.md) |
| POST | `/accounts/{account_id}/r2/temp-access-credentials` | Create Temporary Access Credentials | [View](../operations/r2-create-temp-access-credentials.md) |
