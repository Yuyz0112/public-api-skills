# waitingroom_turnstile_action

Which action to take when a bot is detected using Turnstile. `log` will
have no impact on queueing behavior, simply keeping track of how many
bots are detected in Waiting Room Analytics. `infinite_queue` will send
bots to a false queueing state, where they will never reach your
origin. `infinite_queue` requires Advanced Waiting Room.


**Type:** enum

## Values

- `log`
- `infinite_queue`
