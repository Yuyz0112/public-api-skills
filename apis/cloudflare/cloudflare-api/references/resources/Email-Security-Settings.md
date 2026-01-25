# Email Security Settings

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/email-security/settings/allow_policies` | List email allow policies | [View](../operations/email-security-list-allow-policies.md) |
| POST | `/accounts/{account_id}/email-security/settings/allow_policies` | Create an email allow policy | [View](../operations/email-security-create-allow-policy.md) |
| POST | `/accounts/{account_id}/email-security/settings/allow_policies/batch` | Batch Allow Policies | [View](../operations/email-security-batch-allow-policies.md) |
| GET | `/accounts/{account_id}/email-security/settings/allow_policies/{policy_id}` | Get an email allow policy | [View](../operations/email-security-get-allow-policy.md) |
| DELETE | `/accounts/{account_id}/email-security/settings/allow_policies/{policy_id}` | Delete an email allow policy | [View](../operations/email-security-delete-allow-policy.md) |
| PATCH | `/accounts/{account_id}/email-security/settings/allow_policies/{policy_id}` | Update an email allow policy | [View](../operations/email-security-update-allow-policy.md) |
| GET | `/accounts/{account_id}/email-security/settings/block_senders` | List blocked email senders | [View](../operations/email-security-list-blocked-senders.md) |
| POST | `/accounts/{account_id}/email-security/settings/block_senders` | Create a blocked email sender | [View](../operations/email-security-create-blocked-sender.md) |
| POST | `/accounts/{account_id}/email-security/settings/block_senders/batch` | Batch Block Senders | [View](../operations/email-security-batch-blocked-senders.md) |
| GET | `/accounts/{account_id}/email-security/settings/block_senders/{pattern_id}` | Get a blocked email sender | [View](../operations/email-security-get-blocked-sender.md) |
| DELETE | `/accounts/{account_id}/email-security/settings/block_senders/{pattern_id}` | Delete a blocked email sender | [View](../operations/email-security-delete-blocked-sender.md) |
| PATCH | `/accounts/{account_id}/email-security/settings/block_senders/{pattern_id}` | Update a blocked email sender | [View](../operations/email-security-update-blocked-sender.md) |
| GET | `/accounts/{account_id}/email-security/settings/domains` | List protected email domains | [View](../operations/email-security-list-domains.md) |
| DELETE | `/accounts/{account_id}/email-security/settings/domains` | Unprotect multiple email domains | [View](../operations/email-security-delete-domains.md) |
| GET | `/accounts/{account_id}/email-security/settings/domains/{domain_id}` | Get an email domain | [View](../operations/email-security-get-domain.md) |
| DELETE | `/accounts/{account_id}/email-security/settings/domains/{domain_id}` | Unprotect an email domain | [View](../operations/email-security-delete-domain.md) |
| PATCH | `/accounts/{account_id}/email-security/settings/domains/{domain_id}` | Update an email domain | [View](../operations/email-security-update-domain.md) |
| GET | `/accounts/{account_id}/email-security/settings/impersonation_registry` | List entries in impersonation registry | [View](../operations/email-security-list-display-names.md) |
| POST | `/accounts/{account_id}/email-security/settings/impersonation_registry` | Create an entry in impersonation registry | [View](../operations/email-security-create-display-name.md) |
| GET | `/accounts/{account_id}/email-security/settings/impersonation_registry/{display_name_id}` | Get an entry in impersonation registry | [View](../operations/email-security-get-display-name.md) |
| DELETE | `/accounts/{account_id}/email-security/settings/impersonation_registry/{display_name_id}` | Delete an entry from impersonation registry | [View](../operations/email-security-delete-display-name.md) |
| PATCH | `/accounts/{account_id}/email-security/settings/impersonation_registry/{display_name_id}` | Update an entry in impersonation registry | [View](../operations/email-security-update-display-name.md) |
| POST | `/accounts/{account_id}/email-security/settings/sending_domain_restrictions/batch` | Batch Sending Domain Restrictions | [View](../operations/email-security-batch-sending-domain-restrictions.md) |
| GET | `/accounts/{account_id}/email-security/settings/trusted_domains` | List trusted email domains | [View](../operations/email-security-list-trusted-domains.md) |
| POST | `/accounts/{account_id}/email-security/settings/trusted_domains` | Create a trusted email domain | [View](../operations/email-security-create-trusted-domain.md) |
| POST | `/accounts/{account_id}/email-security/settings/trusted_domains/batch` | Batch Trusted Domains | [View](../operations/email-security-batch-trusted-domains.md) |
| GET | `/accounts/{account_id}/email-security/settings/trusted_domains/{trusted_domain_id}` | Get a trusted email domain | [View](../operations/email-security-get-trusted-domain.md) |
| DELETE | `/accounts/{account_id}/email-security/settings/trusted_domains/{trusted_domain_id}` | Delete a trusted email domain | [View](../operations/email-security-delete-trusted-domain.md) |
| PATCH | `/accounts/{account_id}/email-security/settings/trusted_domains/{trusted_domain_id}` | Update a trusted email domain | [View](../operations/email-security-update-trusted-domain.md) |
