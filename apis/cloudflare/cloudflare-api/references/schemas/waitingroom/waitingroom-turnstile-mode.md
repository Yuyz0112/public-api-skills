# waitingroom_turnstile_mode

Which Turnstile widget type to use for detecting bot traffic. See
[the Turnstile documentation](https://developers.cloudflare.com/turnstile/concepts/widget/#widget-types)
for the definitions of these widget types. Set to `off` to disable the
Turnstile integration entirely. Setting this to anything other than
`off` or `invisible` requires Advanced Waiting Room.


**Type:** enum

## Values

- `off`
- `invisible`
- `visible_non_interactive`
- `visible_managed`
