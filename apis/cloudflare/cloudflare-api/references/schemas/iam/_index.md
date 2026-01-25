# iam Schemas

140 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [iam_access](iam-access.md) | enum | Allow or deny operations against the resources. |
| [iam_account](iam-account.md) | object |  |
| [iam_account-type](iam-account-type.md) | enum |  |
| [iam_account_identifier](iam-account-identifier.md) | allOf | Account identifier tag. |
| [iam_api-response-collection](iam-api-response-collection.md) | allOf |  |
| [iam_api-response-common](iam-api-response-common.md) | object |  |
| [iam_api-response-common-failure](iam-api-response-common-failure.md) | object |  |
| [iam_api-response-single](iam-api-response-single.md) | allOf |  |
| [iam_api-response-single-id](iam-api-response-single-id.md) | allOf |  |
| [iam_api_access_enabled](iam-api-access-enabled.md) | primitive | Enterprise only. Indicates whether or not API acce |
| [iam_cidr_list](iam-cidr-list.md) | array | List of IPv4/IPv6 CIDR addresses. |
| [iam_code](iam-code.md) | primitive | The unique activation code for the account members |
| [iam_collection_member_response_with_policies](iam-collection-member-response-with-policies.md) | allOf |  |
| [iam_collection_membership_response](iam-collection-membership-response.md) | allOf |  |
| [iam_collection_membership_response_with_policies](iam-collection-membership-response-with-policies.md) | allOf |  |
| [iam_collection_organization_response](iam-collection-organization-response.md) | allOf |  |
| [iam_collection_permission_groups_response](iam-collection-permission-groups-response.md) | allOf |  |
| [iam_collection_role_response](iam-collection-role-response.md) | allOf |  |
| [iam_collection_tokens_response](iam-collection-tokens-response.md) | allOf |  |
| [iam_common_components-schemas-identifier](iam-common-components-schemas-identifier.md) | primitive | Identifier |
| [iam_components-schemas-account](iam-components-schemas-account.md) | allOf |  |
| [iam_components-schemas-status](iam-components-schemas-status.md) | enum | Whether the user is a member of the organization o |
| [iam_condition](iam-condition.md) | object |  |
| [iam_country](iam-country.md) | primitive | The country in which the user lives. |
| [iam_create-account](iam-create-account.md) | object |  |
| [iam_create-member-with-policies](iam-create-member-with-policies.md) | object |  |
| [iam_create-member-with-roles](iam-create-member-with-roles.md) | object |  |
| [iam_create-scope](iam-create-scope.md) | object | A scope is a combination of scope objects which pr |
| [iam_create_member_policy](iam-create-member-policy.md) | object |  |
| [iam_create_payload](iam-create-payload.md) | object |  |
| [iam_create_resource_group_scope_scope_key](iam-create-resource-group-scope-scope-key.md) | primitive | This is a combination of pre-defined resource name |
| [iam_create_resource_group_scope_scope_object](iam-create-resource-group-scope-scope-object.md) | object | A scope object represents any resource that can ha |
| [iam_create_resource_group_scope_scope_object_key](iam-create-resource-group-scope-scope-object-key.md) | primitive | This is a combination of pre-defined resource name |
| [iam_create_user_group_body](iam-create-user-group-body.md) | object |  |
| [iam_dns_verification_code](iam-dns-verification-code.md) | primitive | DNS verification code. Add this entire string to t |
| [iam_effect](iam-effect.md) | enum | Allow or deny operations against the resources. |
| [iam_email](iam-email.md) | primitive | The contact email address of the user. |
| [iam_expires_on](iam-expires-on.md) | primitive | The expiration time on or after which the JWT MUST |
| [iam_first_name](iam-first-name.md) | primitive | User's first name |
| [iam_grants](iam-grants.md) | object |  |
| [iam_invite_components-schemas-identifier](iam-invite-components-schemas-identifier.md) | primitive | Invite identifier tag. |
| [iam_invited_by](iam-invited-by.md) | primitive | The email address of the user who created the invi |
| [iam_invited_member_email](iam-invited-member-email.md) | primitive | Email address of the user to add to the organizati |
| [iam_invited_on](iam-invited-on.md) | primitive | When the invite was sent. |
| [iam_issued_on](iam-issued-on.md) | primitive | The time on which the token was created. |
| [iam_last_name](iam-last-name.md) | primitive | User's last name |
| [iam_last_used_on](iam-last-used-on.md) | primitive | Last time the token was used. |
| [iam_list_member_policy](iam-list-member-policy.md) | object |  |
| [iam_member_permission_group](iam-member-permission-group.md) | object | A group of permissions. |
| [iam_member_permission_groups](iam-member-permission-groups.md) | array | A set of permission groups that are specified to t |
| [iam_member_resource_group](iam-member-resource-group.md) | object | A group of scoped resources. |
| [iam_member_resource_groups](iam-member-resource-groups.md) | array | A list of resource groups that the policy applies  |
| [iam_member_with_policies](iam-member-with-policies.md) | object |  |
| [iam_membership](iam-membership.md) | object |  |
| [iam_membership-with-policies](iam-membership-with-policies.md) | object |  |
| [iam_membership_components-schemas-identifier](iam-membership-components-schemas-identifier.md) | primitive | Membership identifier tag. |
| [iam_messages](iam-messages.md) | array |  |
| [iam_modified_on](iam-modified-on.md) | primitive | Last time the token was modified. |
| [iam_name](iam-name.md) | primitive | Token name. |
| [iam_not_before](iam-not-before.md) | primitive | The time before which the token MUST NOT be accept |
| [iam_organization](iam-organization.md) | object |  |
| [iam_permission_group](iam-permission-group.md) | object | A named group of permissions that map to a group o |
| [iam_permission_group_identifier](iam-permission-group-identifier.md) | allOf | Permission Group identifier tag. |
| [iam_permission_group_ids](iam-permission-group-ids.md) | array | A set of permission groups that are specified to t |
| [iam_permission_groups](iam-permission-groups.md) | array | A set of permission groups that are specified to t |
| [iam_permissions](iam-permissions.md) | object |  |
| [iam_permissions_group_response_collection](iam-permissions-group-response-collection.md) | allOf |  |
| [iam_policy_identifier](iam-policy-identifier.md) | primitive | Policy identifier. |
| [iam_policy_with_permission_groups_and_resources](iam-policy-with-permission-groups-and-resources.md) | object |  |
| [iam_properties-name](iam-properties-name.md) | primitive | Account name |
| [iam_request_create_resource_group](iam-request-create-resource-group.md) | object |  |
| [iam_request_ip](iam-request-ip.md) | object | Client IP restrictions. |
| [iam_request_update_resource_group](iam-request-update-resource-group.md) | object |  |
| [iam_resource_group](iam-resource-group.md) | object | A group of scoped resources. |
| [iam_resource_group_identifier](iam-resource-group-identifier.md) | allOf | Resource Group identifier tag. |
| [iam_resource_group_ids](iam-resource-group-ids.md) | array | A set of resource groups that are specified to the |
| [iam_resource_groups](iam-resource-groups.md) | array | A list of resource groups that the policy applies  |
| [iam_resources](iam-resources.md) | oneOf | A list of resource names that the policy applies t |
| [iam_resources_type_object_nested](iam-resources-type-object-nested.md) | object | Map of nested resource permissions |
| [iam_resources_type_object_string](iam-resources-type-object-string.md) | object | Map of simple string resource permissions |
| [iam_response_collection](iam-response-collection.md) | allOf |  |
| [iam_response_collection_accounts](iam-response-collection-accounts.md) | allOf |  |
| [iam_response_create](iam-response-create.md) | allOf |  |
| [iam_response_single](iam-response-single.md) | allOf |  |
| [iam_response_single_account](iam-response-single-account.md) | allOf |  |
| [iam_response_single_value](iam-response-single-value.md) | allOf |  |
| [iam_result_info](iam-result-info.md) | object |  |
| [iam_role](iam-role.md) | object |  |
| [iam_role_components-schemas-identifier](iam-role-components-schemas-identifier.md) | primitive | Role identifier tag. |
| [iam_role_names](iam-role-names.md) | array | List of role names the membership has for this acc |
| [iam_schemas-account](iam-schemas-account.md) | allOf |  |
| [iam_schemas-collection_invite_response](iam-schemas-collection-invite-response.md) | allOf |  |
| [iam_schemas-expires_on](iam-schemas-expires-on.md) | primitive | When the invite is no longer active. |
| [iam_schemas-messages](iam-schemas-messages.md) | array |  |
| [iam_schemas-name](iam-schemas-name.md) | primitive | Organization name. |
| [iam_schemas-permissions](iam-schemas-permissions.md) | array | Access permissions for this User. |
| [iam_schemas-status](iam-schemas-status.md) | enum | Status of this membership. |
| [iam_scope](iam-scope.md) | object | A scope is a combination of scope objects which pr |
| [iam_scope_key](iam-scope-key.md) | primitive | This is a combination of pre-defined resource name |
| [iam_scope_object](iam-scope-object.md) | object | A scope object represents any resource that can ha |
| [iam_scope_object_key](iam-scope-object-key.md) | primitive | This is a combination of pre-defined resource name |
| [iam_single_invite_response](iam-single-invite-response.md) | allOf |  |
| [iam_single_member_response_with_policies](iam-single-member-response-with-policies.md) | allOf |  |
| [iam_single_membership_response](iam-single-membership-response.md) | allOf |  |
| [iam_single_membership_response_with_policies](iam-single-membership-response-with-policies.md) | allOf |  |
| [iam_single_organization_response](iam-single-organization-response.md) | allOf |  |
| [iam_single_permission_groups_response](iam-single-permission-groups-response.md) | allOf |  |
| [iam_single_role_response](iam-single-role-response.md) | allOf |  |
| [iam_single_token_create_response](iam-single-token-create-response.md) | allOf |  |
| [iam_single_token_response](iam-single-token-response.md) | allOf |  |
| [iam_single_user_response](iam-single-user-response.md) | allOf |  |
| [iam_sso_connector](iam-sso-connector.md) | object |  |
| [iam_sso_connector_collection_response](iam-sso-connector-collection-response.md) | allOf |  |
| [iam_sso_connector_identifier](iam-sso-connector-identifier.md) | allOf | SSO Connector identifier tag. |
| [iam_sso_connector_response](iam-sso-connector-response.md) | allOf |  |
| [iam_sso_connector_verification_info](iam-sso-connector-verification-info.md) | object |  |
| [iam_telephone](iam-telephone.md) | primitive | User's telephone number |
| [iam_token_base](iam-token-base.md) | object |  |
| [iam_token_body](iam-token-body.md) | allOf |  |
| [iam_token_identifier](iam-token-identifier.md) | primitive | Token identifier tag. |
| [iam_token_policies](iam-token-policies.md) | array | List of access policies assigned to the token. |
| [iam_token_status](iam-token-status.md) | enum | Status of the token. |
| [iam_token_verify_response_single_segment](iam-token-verify-response-single-segment.md) | allOf |  |
| [iam_token_with_value](iam-token-with-value.md) | allOf |  |
| [iam_two_factor_authentication_enabled](iam-two-factor-authentication-enabled.md) | primitive | Indicates whether two-factor authentication is ena |
| [iam_two_factor_authentication_locked](iam-two-factor-authentication-locked.md) | primitive | Indicates whether two-factor authentication is req |
| [iam_unit-identifier](iam-unit-identifier.md) | primitive | Tenant unit identifier. |
| [iam_update-member-with-policies](iam-update-member-with-policies.md) | object |  |
| [iam_update-member-with-roles](iam-update-member-with-roles.md) | object |  |
| [iam_update_user_group_body](iam-update-user-group-body.md) | object |  |
| [iam_use_fedramp_language](iam-use-fedramp-language.md) | primitive | Controls the display of FedRAMP language to the us |
| [iam_user_group](iam-user-group.md) | object | A group of policies resources. |
| [iam_user_group_identifier](iam-user-group-identifier.md) | allOf | User Group identifier tag. |
| [iam_user_group_member](iam-user-group-member.md) | object | Member attached to a User Group. |
| [iam_user_group_member_identifier](iam-user-group-member-identifier.md) | allOf | The identifier of an existing account Member. |
| [iam_user_group_policy_write_body](iam-user-group-policy-write-body.md) | object |  |
| [iam_user_groups](iam-user-groups.md) | array | A list of user groups for the account. |
| [iam_user_invite](iam-user-invite.md) | object |  |
| [iam_value](iam-value.md) | primitive | The token value. |
| [iam_zipcode](iam-zipcode.md) | primitive | The zipcode or postal code where the user lives. |
