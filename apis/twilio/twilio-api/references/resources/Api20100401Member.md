# Api20100401Member

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/2010-04-01/Accounts/{AccountSid}/Queues/{QueueSid}/Members/{CallSid}.json` | Fetch a specific member from the queue | [View](../operations/FetchMember.md) |
| POST | `/2010-04-01/Accounts/{AccountSid}/Queues/{QueueSid}/Members/{CallSid}.json` | Dequeue a member from a queue and have the member's call begin executing the TwiML document at that URL | [View](../operations/UpdateMember.md) |
| GET | `/2010-04-01/Accounts/{AccountSid}/Queues/{QueueSid}/Members.json` | Retrieve the members of the queue | [View](../operations/ListMember.md) |
