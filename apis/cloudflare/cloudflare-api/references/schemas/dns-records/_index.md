# dns-records Schemas

66 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [dns-records_AAAARecord](dns-records-AAAARecord.md) | allOf |  |
| [dns-records_ARecord](dns-records-ARecord.md) | allOf |  |
| [dns-records_CAARecord](dns-records-CAARecord.md) | allOf |  |
| [dns-records_CERTRecord](dns-records-CERTRecord.md) | allOf |  |
| [dns-records_CNAMERecord](dns-records-CNAMERecord.md) | allOf |  |
| [dns-records_DNSKEYRecord](dns-records-DNSKEYRecord.md) | allOf |  |
| [dns-records_DSRecord](dns-records-DSRecord.md) | allOf |  |
| [dns-records_HTTPSRecord](dns-records-HTTPSRecord.md) | allOf |  |
| [dns-records_LOCRecord](dns-records-LOCRecord.md) | allOf |  |
| [dns-records_MXRecord](dns-records-MXRecord.md) | allOf |  |
| [dns-records_NAPTRRecord](dns-records-NAPTRRecord.md) | allOf |  |
| [dns-records_NSRecord](dns-records-NSRecord.md) | allOf |  |
| [dns-records_OPENPGPKEYRecord](dns-records-OPENPGPKEYRecord.md) | allOf |  |
| [dns-records_PTRRecord](dns-records-PTRRecord.md) | allOf |  |
| [dns-records_SMIMEARecord](dns-records-SMIMEARecord.md) | allOf |  |
| [dns-records_SRVRecord](dns-records-SRVRecord.md) | allOf |  |
| [dns-records_SSHFPRecord](dns-records-SSHFPRecord.md) | allOf |  |
| [dns-records_SVCBRecord](dns-records-SVCBRecord.md) | allOf |  |
| [dns-records_TLSARecord](dns-records-TLSARecord.md) | allOf |  |
| [dns-records_TXTRecord](dns-records-TXTRecord.md) | allOf |  |
| [dns-records_URIRecord](dns-records-URIRecord.md) | allOf |  |
| [dns-records_api-response-collection](dns-records-api-response-collection.md) | allOf |  |
| [dns-records_api-response-common](dns-records-api-response-common.md) | object |  |
| [dns-records_api-response-common-failure](dns-records-api-response-common-failure.md) | object |  |
| [dns-records_api-response-single](dns-records-api-response-single.md) | allOf |  |
| [dns-records_comment](dns-records-comment.md) | primitive | Comments or notes about the DNS record. This field |
| [dns-records_direction](dns-records-direction.md) | enum | Direction to order DNS records in. |
| [dns-records_dns-record-batch-delete](dns-records-dns-record-batch-delete.md) | allOf |  |
| [dns-records_dns-record-batch-patch](dns-records-dns-record-batch-patch.md) | allOf |  |
| [dns-records_dns-record-batch-post](dns-records-dns-record-batch-post.md) | allOf |  |
| [dns-records_dns-record-batch-put](dns-records-dns-record-batch-put.md) | allOf |  |
| [dns-records_dns-record-patch](dns-records-dns-record-patch.md) | anyOf |  |
| [dns-records_dns-record-post](dns-records-dns-record-post.md) | anyOf |  |
| [dns-records_dns-record-response](dns-records-dns-record-response.md) | allOf |  |
| [dns-records_dns-record-scan-batch-accept](dns-records-dns-record-scan-batch-accept.md) | allOf |  |
| [dns-records_dns-record-scan-batch-reject](dns-records-dns-record-scan-batch-reject.md) | allOf |  |
| [dns-records_dns-record-shared-fields](dns-records-dns-record-shared-fields.md) | object |  |
| [dns-records_dns-record-with-data](dns-records-dns-record-with-data.md) | oneOf |  |
| [dns-records_dns-record-without-data](dns-records-dns-record-without-data.md) | oneOf |  |
| [dns-records_dns-request-batch-object](dns-records-dns-request-batch-object.md) | object |  |
| [dns-records_dns-request-review-scan-object](dns-records-dns-request-review-scan-object.md) | object |  |
| [dns-records_dns-response-batch-object](dns-records-dns-response-batch-object.md) | object |  |
| [dns-records_dns-response-review-scan-object](dns-records-dns-response-review-scan-object.md) | object |  |
| [dns-records_dns_response_account_usage](dns-records-dns-response-account-usage.md) | allOf |  |
| [dns-records_dns_response_batch](dns-records-dns-response-batch.md) | allOf |  |
| [dns-records_dns_response_collection](dns-records-dns-response-collection.md) | allOf |  |
| [dns-records_dns_response_import_scan](dns-records-dns-response-import-scan.md) | allOf |  |
| [dns-records_dns_response_review_scan](dns-records-dns-response-review-scan.md) | allOf |  |
| [dns-records_dns_response_single](dns-records-dns-response-single.md) | allOf |  |
| [dns-records_dns_response_trigger_scan](dns-records-dns-response-trigger-scan.md) | allOf |  |
| [dns-records_dns_response_zone_usage](dns-records-dns-response-zone-usage.md) | allOf |  |
| [dns-records_identifier](dns-records-identifier.md) | primitive | Identifier. |
| [dns-records_match](dns-records-match.md) | enum | Whether to match all search requirements or at lea |
| [dns-records_messages](dns-records-messages.md) | array |  |
| [dns-records_name](dns-records-name.md) | primitive | Complete DNS record name, including the zone name, |
| [dns-records_order](dns-records-order.md) | enum | Field to order DNS records by. |
| [dns-records_page](dns-records-page.md) | primitive | Page number of paginated results. |
| [dns-records_per_page](dns-records-per-page.md) | primitive | Number of DNS records per page. |
| [dns-records_priority](dns-records-priority.md) | primitive | Required for MX, SRV and URI records; unused by ot |
| [dns-records_proxied](dns-records-proxied.md) | primitive | Whether the record is receiving the performance an |
| [dns-records_search](dns-records-search.md) | primitive | Allows searching in multiple properties of a DNS r |
| [dns-records_settings](dns-records-settings.md) | object | Settings for the DNS record. |
| [dns-records_tag_match](dns-records-tag-match.md) | enum | Whether to match all tag search requirements or at |
| [dns-records_tags](dns-records-tags.md) | array | Custom tags for the DNS record. This field has no  |
| [dns-records_ttl](dns-records-ttl.md) | anyOf | Time To Live (TTL) of the DNS record in seconds. S |
| [dns-records_type](dns-records-type.md) | enum | Record type. |
