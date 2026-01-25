# Custom Hostname for a Zone

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/zones/{zone_id}/custom_hostnames` | List Custom Hostnames | [View](../operations/custom-hostname-for-a-zone-list-custom-hostnames.md) |
| POST | `/zones/{zone_id}/custom_hostnames` | Create Custom Hostname | [View](../operations/custom-hostname-for-a-zone-create-custom-hostname.md) |
| GET | `/zones/{zone_id}/custom_hostnames/{custom_hostname_id}` | Custom Hostname Details | [View](../operations/custom-hostname-for-a-zone-custom-hostname-details.md) |
| DELETE | `/zones/{zone_id}/custom_hostnames/{custom_hostname_id}` | Delete Custom Hostname (and any issued SSL certificates) | [View](../operations/custom-hostname-for-a-zone-delete-custom-hostname-and-any-issued-ssl-certificates.md) |
| PATCH | `/zones/{zone_id}/custom_hostnames/{custom_hostname_id}` | Edit Custom Hostname | [View](../operations/custom-hostname-for-a-zone-edit-custom-hostname.md) |
| PUT | `/zones/{zone_id}/custom_hostnames/{custom_hostname_id}/certificate_pack/{certificate_pack_id}/certificates/{certificate_id}` | Replace Custom Certificate and Custom Key In Custom Hostname | [View](../operations/custom-hostname-for-a-zone-edit-custom-certificate-custom-hostname.md) |
| DELETE | `/zones/{zone_id}/custom_hostnames/{custom_hostname_id}/certificate_pack/{certificate_pack_id}/certificates/{certificate_id}` | Delete Single Certificate And Key For Custom Hostname | [View](../operations/custom-hostname-for-a-zone-delete-single-certificate-and-key-in-a-custom-hostname.md) |
