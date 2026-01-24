# POST /v1/terminal/onboarding_links

**Resource:** [terminal](../resources/terminal.md)
**Create an Onboarding Link**
**Operation ID:** `PostTerminalOnboardingLinks`

<p>Creates a new <code>OnboardingLink</code> object that contains a redirect_url used for onboarding onto Tap to Pay on iPhone.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[terminal.onboarding_link](../schemas/terminal-onboarding/terminal-onboarding-link.md)

