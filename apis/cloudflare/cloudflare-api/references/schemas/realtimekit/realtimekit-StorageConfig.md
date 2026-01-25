# realtimekit_StorageConfig

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `access_key` | string | No | Access key of the storage medium. Access key is not required for the `gcs` storage media type.

Note that this field is not readable by clients, only writeable. |
| `auth_method` | enum: KEY, PASSWORD | No | Authentication method used for "sftp" type storage medium
 |
| `bucket` | string | No | Name of the storage medium's bucket. |
| `host` | string | No | SSH destination server host for SFTP type storage medium |
| `password` | string | No | SSH destination server password for SFTP type storage medium when auth_method is "PASSWORD". If auth_method is "KEY", this specifies the password for the ssh private key. |
| `path` | string | No | Path relative to the bucket root at which the recording will be placed. |
| `port` | number | No | SSH destination server port for SFTP type storage medium |
| `private_key` | string | No | Private key used to login to destination SSH server for SFTP type storage medium, when auth_method used is "KEY" |
| `region` | string | No | Region of the storage medium. |
| `secret` | string | No | Secret key of the storage medium. Similar to `access_key`, it is only writeable by clients, not readable. |
| `type` | enum: aws, azure, digitalocean... | Yes | Type of storage media. |
| `username` | string | No | SSH destination server username for SFTP type storage medium |

