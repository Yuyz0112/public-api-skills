# zaraz_zaraz-config-base

Zaraz configuration

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `analytics` | object | No | Cloudflare Monitoring settings. |
| `consent` | object | No | Consent management configuration. |
| `dataLayer` | boolean | Yes | Data layer compatibility mode enabled. |
| `debugKey` | string | Yes | The key for Zaraz debug mode. |
| `historyChange` | boolean | No | Single Page Application support enabled. |
| `settings` | object | Yes | General Zaraz settings. |
| `triggers` | object | Yes | Triggers set up under Zaraz configuration, where key is the trigger alpha-numeric ID and value is the trigger configuration. |
| `variables` | object | Yes | Variables set up under Zaraz configuration, where key is the variable alpha-numeric ID and value is the variable configuration. Values of variables of type secret are not included. |
| `zarazVersion` | integer | Yes | Zaraz internal version of the config. |

## Nested Fields

### `analytics`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `defaultPurpose` | string | No | Consent purpose assigned to Monitoring. |
| `enabled` | boolean | No | Whether Advanced Monitoring reports are enabled. |
| `sessionExpTime` | integer | No | Session expiration time (seconds). |

### `consent`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `buttonTextTranslations` | object | No |  |
| `companyEmail` | string | No |  |
| `companyName` | string | No |  |
| `companyStreetAddress` | string | No |  |
| `consentModalIntroHTML` | string | No |  |
| `consentModalIntroHTMLWithTranslations` | object | No | Object where keys are language codes |
| `cookieName` | string | No |  |
| `customCSS` | string | No |  |
| `customIntroDisclaimerDismissed` | boolean | No |  |
| `defaultLanguage` | string | No |  |
| `enabled` | boolean | Yes |  |
| `hideModal` | boolean | No |  |
| `purposes` | object | No | Object where keys are purpose alpha-numeric IDs |
| `purposesWithTranslations` | object | No | Object where keys are purpose alpha-numeric IDs |
| `tcfCompliant` | boolean | No |  |

#### `consent.buttonTextTranslations`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accept_all` | object | Yes | Object where keys are language codes |
| `confirm_my_choices` | object | Yes | Object where keys are language codes |
| `reject_all` | object | Yes | Object where keys are language codes |

### `settings`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `autoInjectScript` | boolean | Yes | Automatic injection of Zaraz scripts enabled. |
| `contextEnricher` | object | No | Details of the worker that receives and edits Zaraz Context object. |
| `cookieDomain` | string | No | The domain Zaraz will use for writing and reading its cookies. |
| `ecommerce` | boolean | No | Ecommerce API enabled. |
| `eventsApiPath` | string | No | Custom endpoint for server-side track events. |
| `hideExternalReferer` | boolean | No | Hiding external referrer URL enabled. |
| `hideIPAddress` | boolean | No | Trimming IP address enabled. |
| `hideQueryParams` | boolean | No | Removing URL query params enabled. |
| `hideUserAgent` | boolean | No | Removing sensitive data from User Aagent string enabled. |
| `initPath` | string | No | Custom endpoint for Zaraz init script. |
| `injectIframes` | boolean | No | Injection of Zaraz scripts into iframes enabled. |
| `mcRootPath` | string | No | Custom path for Managed Components server functionalities. |
| `scriptPath` | string | No | Custom endpoint for Zaraz main script. |
| `trackPath` | string | No | Custom endpoint for Zaraz tracking requests. |

#### `settings.contextEnricher`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `escapedWorkerName` | string | Yes |  |
| `workerTag` | string | Yes |  |

