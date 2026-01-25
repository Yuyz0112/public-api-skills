# rulesets Schemas

102 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [rulesets_AccountId](rulesets-AccountId.md) | primitive | The unique ID of the account. |
| [rulesets_BlockRule](rulesets-BlockRule.md) | allOf |  |
| [rulesets_ChallengeRule](rulesets-ChallengeRule.md) | allOf |  |
| [rulesets_CompressResponseRule](rulesets-CompressResponseRule.md) | allOf |  |
| [rulesets_Cursor](rulesets-Cursor.md) | primitive | The cursor to use for the next page. |
| [rulesets_DDoSDynamicRule](rulesets-DDoSDynamicRule.md) | allOf |  |
| [rulesets_Errors](rulesets-Errors.md) | array | A list of error messages. |
| [rulesets_ExecuteCategoryOverrides](rulesets-ExecuteCategoryOverrides.md) | array | A list of category-level overrides. This option ha |
| [rulesets_ExecuteMatchedData](rulesets-ExecuteMatchedData.md) | object | The configuration to use for matched data logging. |
| [rulesets_ExecuteOverrides](rulesets-ExecuteOverrides.md) | object | A set of overrides to apply to the target ruleset. |
| [rulesets_ExecuteRule](rulesets-ExecuteRule.md) | allOf |  |
| [rulesets_ExecuteRuleOverrides](rulesets-ExecuteRuleOverrides.md) | array | A list of rule-level overrides. This option has th |
| [rulesets_ExecuteSensitivityLevel](rulesets-ExecuteSensitivityLevel.md) | enum |  |
| [rulesets_ForceConnectionCloseRule](rulesets-ForceConnectionCloseRule.md) | allOf |  |
| [rulesets_JsChallengeRule](rulesets-JsChallengeRule.md) | allOf |  |
| [rulesets_LogCustomFieldCookieFields](rulesets-LogCustomFieldCookieFields.md) | array | The cookie fields to log. |
| [rulesets_LogCustomFieldRawResponseFields](rulesets-LogCustomFieldRawResponseFields.md) | array | The raw response fields to log. |
| [rulesets_LogCustomFieldRequestFields](rulesets-LogCustomFieldRequestFields.md) | array | The raw request fields to log. |
| [rulesets_LogCustomFieldResponseFields](rulesets-LogCustomFieldResponseFields.md) | array | The transformed response fields to log. |
| [rulesets_LogCustomFieldRule](rulesets-LogCustomFieldRule.md) | allOf |  |
| [rulesets_LogCustomFieldTransformedRequestFields](rulesets-LogCustomFieldTransformedRequestFields.md) | array | The transformed request fields to log. |
| [rulesets_LogRule](rulesets-LogRule.md) | allOf |  |
| [rulesets_ManagedChallengeRule](rulesets-ManagedChallengeRule.md) | allOf |  |
| [rulesets_ManagedTransform](rulesets-ManagedTransform.md) | object | A Managed Transform object. |
| [rulesets_ManagedTransformId](rulesets-ManagedTransformId.md) | primitive | The human-readable identifier of the Managed Trans |
| [rulesets_ManagedTransforms](rulesets-ManagedTransforms.md) | object | A Managed Transforms object. |
| [rulesets_Message](rulesets-Message.md) | object | A message. |
| [rulesets_Messages](rulesets-Messages.md) | array | A list of warning messages. |
| [rulesets_PerPage](rulesets-PerPage.md) | primitive | The number of rulesets to return per page. |
| [rulesets_RedirectFromList](rulesets-RedirectFromList.md) | object | A redirect based on a bulk list lookup. |
| [rulesets_RedirectFromValue](rulesets-RedirectFromValue.md) | object | A redirect based on the request properties. |
| [rulesets_RedirectRule](rulesets-RedirectRule.md) | allOf |  |
| [rulesets_RequestRule](rulesets-RequestRule.md) | oneOf |  |
| [rulesets_RequestRules](rulesets-RequestRules.md) | array | The list of rules in the ruleset. |
| [rulesets_Response](rulesets-Response.md) | object | A response object. |
| [rulesets_ResponseRule](rulesets-ResponseRule.md) | allOf |  |
| [rulesets_ResponseRules](rulesets-ResponseRules.md) | array | The list of rules in the ruleset. |
| [rulesets_ResultInfo](rulesets-ResultInfo.md) | object | Information to navigate the results. |
| [rulesets_RewriteHeaderExpression](rulesets-RewriteHeaderExpression.md) | primitive | An expression that evaluates to a value for the he |
| [rulesets_RewriteHeaderOperation](rulesets-RewriteHeaderOperation.md) | primitive | The operation to perform on the header. |
| [rulesets_RewriteHeaderValue](rulesets-RewriteHeaderValue.md) | primitive | A static value for the header. |
| [rulesets_RewriteHeaders](rulesets-RewriteHeaders.md) | object | A map of headers to rewrite. |
| [rulesets_RewriteRule](rulesets-RewriteRule.md) | allOf |  |
| [rulesets_RewriteUri](rulesets-RewriteUri.md) | allOf |  |
| [rulesets_RewriteUriPath](rulesets-RewriteUriPath.md) | object | A URI path rewrite. |
| [rulesets_RewriteUriQuery](rulesets-RewriteUriQuery.md) | object | A URI query rewrite. |
| [rulesets_RouteHostHeader](rulesets-RouteHostHeader.md) | primitive | A value to rewrite the HTTP host header to. |
| [rulesets_RouteOrigin](rulesets-RouteOrigin.md) | object | An origin to route to. |
| [rulesets_RouteRule](rulesets-RouteRule.md) | allOf |  |
| [rulesets_RouteSNI](rulesets-RouteSNI.md) | object | A Server Name Indication (SNI) override. |
| [rulesets_Rule](rulesets-Rule.md) | object |  |
| [rulesets_RuleAction](rulesets-RuleAction.md) | primitive | The action to perform when the rule matches. |
| [rulesets_RuleCategories](rulesets-RuleCategories.md) | array | The categories of the rule. |
| [rulesets_RuleCategory](rulesets-RuleCategory.md) | primitive | The category of a rule. |
| [rulesets_RuleEnabled](rulesets-RuleEnabled.md) | primitive | Whether the rule should be executed. |
| [rulesets_RuleExposedCredentialCheck](rulesets-RuleExposedCredentialCheck.md) | object | Configuration for exposed credential checking. |
| [rulesets_RuleId](rulesets-RuleId.md) | primitive | The unique ID of the rule. |
| [rulesets_RuleLogging](rulesets-RuleLogging.md) | object | An object configuring the rule's logging behavior. |
| [rulesets_RulePosition](rulesets-RulePosition.md) | object | An object configuring where the rule will be place |
| [rulesets_RuleRatelimit](rulesets-RuleRatelimit.md) | object | An object configuring the rule's rate limit behavi |
| [rulesets_Ruleset](rulesets-Ruleset.md) | object | A ruleset object. |
| [rulesets_RulesetId](rulesets-RulesetId.md) | primitive | The unique ID of the ruleset. |
| [rulesets_RulesetKind](rulesets-RulesetKind.md) | enum | The kind of the ruleset. |
| [rulesets_RulesetPhase](rulesets-RulesetPhase.md) | enum | The phase of the ruleset. |
| [rulesets_RulesetVersion](rulesets-RulesetVersion.md) | primitive | The version of the ruleset. |
| [rulesets_ScoreIncrement](rulesets-ScoreIncrement.md) | primitive | A delta to change the score by, which can be eithe |
| [rulesets_ScoreRule](rulesets-ScoreRule.md) | allOf |  |
| [rulesets_ServeErrorAssetName](rulesets-ServeErrorAssetName.md) | primitive | The name of a custom asset to serve as the error r |
| [rulesets_ServeErrorContent](rulesets-ServeErrorContent.md) | primitive | The response content. |
| [rulesets_ServeErrorContentType](rulesets-ServeErrorContentType.md) | enum | The content type header to set with the error resp |
| [rulesets_ServeErrorRule](rulesets-ServeErrorRule.md) | allOf |  |
| [rulesets_ServeErrorStatusCode](rulesets-ServeErrorStatusCode.md) | primitive | The status code to use for the error. |
| [rulesets_SetCacheSettingsAdditionalCacheablePorts](rulesets-SetCacheSettingsAdditionalCacheablePorts.md) | array | A list of additional ports that caching should be  |
| [rulesets_SetCacheSettingsBrowserTTL](rulesets-SetCacheSettingsBrowserTTL.md) | object | How long client browsers should cache the response |
| [rulesets_SetCacheSettingsCache](rulesets-SetCacheSettingsCache.md) | primitive | Whether the request's response from the origin is  |
| [rulesets_SetCacheSettingsCacheKey](rulesets-SetCacheSettingsCacheKey.md) | object | Which components of the request are included in or |
| [rulesets_SetCacheSettingsCacheReserve](rulesets-SetCacheSettingsCacheReserve.md) | object | Settings to determine whether the request's respon |
| [rulesets_SetCacheSettingsCustomCacheKey](rulesets-SetCacheSettingsCustomCacheKey.md) | object | Which components of the request are included or ex |
| [rulesets_SetCacheSettingsCustomCacheKeyCookie](rulesets-SetCacheSettingsCustomCacheKeyCookie.md) | object | Which cookies to include in the cache key. |
| [rulesets_SetCacheSettingsCustomCacheKeyHeader](rulesets-SetCacheSettingsCustomCacheKeyHeader.md) | object | Which headers to include in the cache key. |
| [rulesets_SetCacheSettingsCustomCacheKeyHost](rulesets-SetCacheSettingsCustomCacheKeyHost.md) | object | How to use the host in the cache key. |
| [rulesets_SetCacheSettingsCustomCacheKeyQueryString](rulesets-SetCacheSettingsCustomCacheKeyQueryString.md) | object | Which query string parameters to include in or exc |
| [rulesets_SetCacheSettingsCustomCacheKeyUser](rulesets-SetCacheSettingsCustomCacheKeyUser.md) | object | How to use characteristics of the request user age |
| [rulesets_SetCacheSettingsEdgeTTL](rulesets-SetCacheSettingsEdgeTTL.md) | object | How long the Cloudflare edge network should cache  |
| [rulesets_SetCacheSettingsOriginCacheControl](rulesets-SetCacheSettingsOriginCacheControl.md) | primitive | Whether Cloudflare will aim to strictly adhere to  |
| [rulesets_SetCacheSettingsOriginErrorPagePassthru](rulesets-SetCacheSettingsOriginErrorPagePassthru.md) | primitive | Whether to generate Cloudflare error pages for iss |
| [rulesets_SetCacheSettingsReadTimeout](rulesets-SetCacheSettingsReadTimeout.md) | primitive | A timeout value between two successive read operat |
| [rulesets_SetCacheSettingsRespectStrongEtags](rulesets-SetCacheSettingsRespectStrongEtags.md) | primitive | Whether Cloudflare should respect strong ETag (ent |
| [rulesets_SetCacheSettingsRule](rulesets-SetCacheSettingsRule.md) | allOf |  |
| [rulesets_SetCacheSettingsServeStale](rulesets-SetCacheSettingsServeStale.md) | object | When to serve stale content from cache. |
| [rulesets_SetCacheSettingsStatusCodeTTL](rulesets-SetCacheSettingsStatusCodeTTL.md) | array | A list of TTLs to apply to specific status codes o |
| [rulesets_SetConfigAutominify](rulesets-SetConfigAutominify.md) | object | Which file extensions to minify automatically. |
| [rulesets_SetConfigRule](rulesets-SetConfigRule.md) | allOf |  |
| [rulesets_SkipPhase](rulesets-SkipPhase.md) | enum | A phase to skip the execution of. This option is o |
| [rulesets_SkipPhases](rulesets-SkipPhases.md) | array | A list of phases to skip the execution of. This op |
| [rulesets_SkipProducts](rulesets-SkipProducts.md) | array | A list of legacy security products to skip the exe |
| [rulesets_SkipRule](rulesets-SkipRule.md) | allOf |  |
| [rulesets_SkipRules](rulesets-SkipRules.md) | object | A mapping of ruleset IDs to a list of rule IDs in  |
| [rulesets_SkipRuleset](rulesets-SkipRuleset.md) | enum | A ruleset to skip the execution of. This option is |
| [rulesets_SkipRulesets](rulesets-SkipRulesets.md) | array | A list of ruleset IDs to skip the execution of. Th |
| [rulesets_UrlNormalization](rulesets-UrlNormalization.md) | object | A URL Normalization object. |
| [rulesets_ZoneId](rulesets-ZoneId.md) | primitive | The unique ID of the zone. |
