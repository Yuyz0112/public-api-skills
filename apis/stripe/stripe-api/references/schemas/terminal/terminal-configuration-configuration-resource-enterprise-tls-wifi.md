# terminal_configuration_configuration_resource_enterprise_tls_wifi

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ca_certificate_file` | string | No | A File ID representing a PEM file containing the server certificate |
| `client_certificate_file` | string | Yes | A File ID representing a PEM file containing the client certificate |
| `private_key_file` | string | Yes | A File ID representing a PEM file containing the client RSA private key |
| `private_key_file_password` | string | No | Password for the private key file |
| `ssid` | string | Yes | Name of the WiFi network |

