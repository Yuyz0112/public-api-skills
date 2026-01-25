# zero-trust-gateway_generate-cert-request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `validity_period_days` | integer | No | Sets the certificate validity period in days (range: 1-10,950 days / ~30 years). Defaults to 1,825 days (5 years). **Important**: This field is only settable during the certificate creation.  Certificates becomes immutable after creation - use the `/activate` and `/deactivate` endpoints to manage certificate lifecycle. |

