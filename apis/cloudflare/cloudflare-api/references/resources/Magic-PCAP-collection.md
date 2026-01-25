# Magic PCAP collection

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/pcaps` | List packet capture requests | [View](../operations/magic-pcap-collection-list-packet-capture-requests.md) |
| POST | `/accounts/{account_id}/pcaps` | Create PCAP request | [View](../operations/magic-pcap-collection-create-pcap-request.md) |
| GET | `/accounts/{account_id}/pcaps/ownership` | List PCAPs Bucket Ownership | [View](../operations/magic-pcap-collection-list-pca-ps-bucket-ownership.md) |
| POST | `/accounts/{account_id}/pcaps/ownership` | Add buckets for full packet captures | [View](../operations/magic-pcap-collection-add-buckets-for-full-packet-captures.md) |
| POST | `/accounts/{account_id}/pcaps/ownership/validate` | Validate buckets for full packet captures | [View](../operations/magic-pcap-collection-validate-buckets-for-full-packet-captures.md) |
| DELETE | `/accounts/{account_id}/pcaps/ownership/{ownership_id}` | Delete buckets for full packet captures | [View](../operations/magic-pcap-collection-delete-buckets-for-full-packet-captures.md) |
| GET | `/accounts/{account_id}/pcaps/{pcap_id}` | Get PCAP request | [View](../operations/magic-pcap-collection-get-pcap-request.md) |
| GET | `/accounts/{account_id}/pcaps/{pcap_id}/download` | Download Simple PCAP | [View](../operations/magic-pcap-collection-download-simple-pcap.md) |
| PUT | `/accounts/{account_id}/pcaps/{pcap_id}/stop` | Stop full PCAP | [View](../operations/magic-pcap-collection-stop-full-pcap.md) |
