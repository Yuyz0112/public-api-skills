# bot-management Schemas

40 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [bot-management_ai_bots_protection](bot-management-ai-bots-protection.md) | enum | Enable rule to block AI Scrapers and Crawlers. Ple |
| [bot-management_api-response-common](bot-management-api-response-common.md) | object |  |
| [bot-management_api-response-common-failure](bot-management-api-response-common-failure.md) | object |  |
| [bot-management_api-response-single](bot-management-api-response-single.md) | allOf |  |
| [bot-management_auto_update_model](bot-management-auto-update-model.md) | primitive | Automatically update to the newest bot detection m |
| [bot-management_base_config](bot-management-base-config.md) | allOf |  |
| [bot-management_bm_cookie_enabled](bot-management-bm-cookie-enabled.md) | primitive | Indicates that the bot management cookie can be pl |
| [bot-management_bm_subscription_config](bot-management-bm-subscription-config.md) | allOf |  |
| [bot-management_bot_fight_mode_config](bot-management-bot-fight-mode-config.md) | allOf |  |
| [bot-management_bot_management_response_body](bot-management-bot-management-response-body.md) | allOf |  |
| [bot-management_cf_robots_variant](bot-management-cf-robots-variant.md) | enum | Specifies the Robots Access Control License varian |
| [bot-management_config_single](bot-management-config-single.md) | oneOf |  |
| [bot-management_crawler_protection](bot-management-crawler-protection.md) | enum | Enable rule to punish AI Scrapers and Crawlers via |
| [bot-management_enable_js](bot-management-enable-js.md) | primitive | Use lightweight, invisible JavaScript detections t |
| [bot-management_feedback_report](bot-management-feedback-report.md) | object |  |
| [bot-management_feedback_type](bot-management-feedback-type.md) | enum | Type of feedback report. |
| [bot-management_fight_mode](bot-management-fight-mode.md) | primitive | Whether to enable Bot Fight Mode. |
| [bot-management_fight_mode_turned_on](bot-management-fight-mode-turned-on.md) | primitive | Indicates that the zone's Bot Fight Mode is turned |
| [bot-management_identifier](bot-management-identifier.md) | primitive | Identifier. |
| [bot-management_is_robots_txt_managed](bot-management-is-robots-txt-managed.md) | primitive | Enable cloudflare managed robots.txt. If an existi |
| [bot-management_messages](bot-management-messages.md) | array |  |
| [bot-management_metric_requests](bot-management-metric-requests.md) | object |  |
| [bot-management_optimize_wordpress](bot-management-optimize-wordpress.md) | primitive | Whether to optimize Super Bot Fight Mode protectio |
| [bot-management_optimize_wordpress_turned_on](bot-management-optimize-wordpress-turned-on.md) | primitive | Indicates that the zone's wordpress optimization f |
| [bot-management_requests_by_attribute](bot-management-requests-by-attribute.md) | object | Top attributes contributing to the feedback sample |
| [bot-management_requests_by_score](bot-management-requests-by-score.md) | object | Map of bot scores (1-99) to request counts. Sum mu |
| [bot-management_requests_by_score_src](bot-management-requests-by-score-src.md) | object | Map of score source to request counts. Sum must eq |
| [bot-management_sbfm_definitely_automated](bot-management-sbfm-definitely-automated.md) | enum | Super Bot Fight Mode (SBFM) action to take on defi |
| [bot-management_sbfm_definitely_automated_turned_on](bot-management-sbfm-definitely-automated-turned-on.md) | primitive | Indicates that the zone's definitely automated req |
| [bot-management_sbfm_definitely_config](bot-management-sbfm-definitely-config.md) | allOf |  |
| [bot-management_sbfm_likely_automated](bot-management-sbfm-likely-automated.md) | enum | Super Bot Fight Mode (SBFM) action to take on like |
| [bot-management_sbfm_likely_automated_turned_on](bot-management-sbfm-likely-automated-turned-on.md) | primitive | Indicates that the zone's likely automated request |
| [bot-management_sbfm_likely_config](bot-management-sbfm-likely-config.md) | allOf |  |
| [bot-management_sbfm_static_resource_protection](bot-management-sbfm-static-resource-protection.md) | primitive | Super Bot Fight Mode (SBFM) to enable static resou |
| [bot-management_sbfm_static_resource_protection_turned_on](bot-management-sbfm-static-resource-protection-turned-on.md) | primitive | Indicates that the zone's static resource protecti |
| [bot-management_sbfm_verified_bots](bot-management-sbfm-verified-bots.md) | enum | Super Bot Fight Mode (SBFM) action to take on veri |
| [bot-management_sbfm_verified_bots_turned_on](bot-management-sbfm-verified-bots-turned-on.md) | primitive | Indicates that the zone's verified bot requests ar |
| [bot-management_suppress_session_score](bot-management-suppress-session-score.md) | primitive | Whether to disable tracking the highest bot score  |
| [bot-management_suppress_session_score_turned_off](bot-management-suppress-session-score-turned-off.md) | primitive | Indicates that the zone's session score tracking i |
| [bot-management_using_latest_model](bot-management-using-latest-model.md) | primitive | A read-only field that indicates whether the zone  |
